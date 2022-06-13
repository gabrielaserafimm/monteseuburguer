<template>
    <div>
        <h2>Descrição da pessoa:</h2>
        <Info/>
    </div>
</template>

<script>
import Info from './Info'

    export default {
        name: 'Pessoa',
        components: {
            Info
        },
        data() {
            return {
                nome: 'Gabriela'
            }
        }    
    }
</script>