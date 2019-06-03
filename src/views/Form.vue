<template>
    <div>
        <h1>Fromulario</h1>
        <form>
            <b-row>
                <b-col cols="12">
                    <b-form-input type="text" v-model="texto" :state="valida" ></b-form-input>
                    {{texto}}
                </b-col>
            </b-row>
        </form>
    </div>
</template>

<script>
import { truncate } from 'fs';
export default {
    name:'form',
    data(){
        return{
            texto:''
        }
    },
    computed:{
        valida(){
            return this.texto.length > 5 ? true : false
        }
    }
}
</script>
