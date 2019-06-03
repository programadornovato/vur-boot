<template>
    <div>
        <div class="mt-5">
            <b-button variant="danger" >boton</b-button>
            <b-button variant="warning" >boton</b-button>
            <b-button variant="success" >boton</b-button>
            <b-button variant="primary" >boton</b-button>
            <b-button variant="dark" >boton</b-button>
        </div>
        <div class="mt-5">
            <b-card
                title="Card Title"
                img-src="https://picsum.photos/600/300/?image=25"
                img-alt="Image"
                img-top
                tag="article"
                style="max-width: 20rem;"
                class="mb-2"
            >
                <b-card-text>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Officiis repellendus velit iure temporibus labore odit quaerat ea provident, est quasi dolores! Incidunt laudantium dignissimos est quaerat enim eaque reprehenderit nostrum?</b-card-text>
                <b-button variant="primary" href="#" > Boton</b-button>
            </b-card>
        </div>
    </div>
    
</template>
<script>
export default {
    name:'card'
}
</script>

