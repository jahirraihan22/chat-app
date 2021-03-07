<template>
    <div>
        <b>{{ message.user.name }} : </b> {{ message.message }} 
    </div>
</template>

<script>
export default {
    props : ['message']
}
</script>