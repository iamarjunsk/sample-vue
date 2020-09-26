<template>
    <div>
        <h3>Dev: {{developer}}</h3>
    </div>

</template>

<script>
export default {
    data(){
        return{
            developer:"Arjun SK"
        };
    },
    methods:{
        heloWld(){
            alert("helo Arjun");
            this.developer="Sk"
        }
    },
    mounted(){
        console.log(this);
        this.heloWld()
    }
}
</script>

<style scoped>

</style>