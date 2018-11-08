<template>
    <div>
        <h1>product ID is {{$route.params.pid}}</h1>
    </div>
</template>
<script>
export default {
    validate(data){
        return data.params.pid == 1
    }
}
</script>
