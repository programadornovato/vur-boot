<template>
    <div>
        <h1>Select</h1>
        <form>
            <b-row>
                <b-col cols="4">
                    <b-form-select v-model="select" :options="arraySelect" ></b-form-select>
                    {{select}}
                </b-col>
                <b-col cols="4">
                    <b-form-radio-group v-model="radio" :options="arrayRadio" ></b-form-radio-group>
                    {{radio}}
                </b-col>
                <b-col cols="4">
                    <b-form-checkbox-group v-model="check" :options="arrayCheck" ></b-form-checkbox-group>
                    {{check}}
                </b-col>
            </b-row>
        </form>
    </div>
</template>

<script>
export default {
    name:'select',
    data(){

        return{
            select:'elemento1',
            arraySelect:[
                {value:null,text:"Seleccione un elemento"},
                {value:'elemento1',text:"Elemento 1"},
                {value:'elemento2',text:"Elemento 2"},
                {value:'elemento3',text:"Elemento 3"},
                {value:'elemento4',text:"Elemento 4"},
            ]
            ,
            radio:'elemento1',
            arrayRadio:[
                {value:null,text:"Seleccione un elemento"},
                {value:'elemento1',text:"Elemento 1"},
                {value:'elemento2',text:"Elemento 2"},
                {value:'elemento3',text:"Elemento 3"},
                {value:'elemento4',text:"Elemento 4"},
            ]
            ,
            check:['elemento1','elemento2'],
            arrayCheck:[
                {value:null,text:"Seleccione un elemento"},
                {value:'elemento1',text:"Elemento 1"},
                {value:'elemento2',text:"Elemento 2"},
                {value:'elemento3',text:"Elemento 3"},
                {value:'elemento4',text:"Elemento 4"},
            ]

        }
    },
    computed:{
    }
}
</script>
