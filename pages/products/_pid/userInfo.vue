<template>
    <div>
        this is a userinfo page with pid: {{$route.params.pid}}
    </div>
</template>

<script>
export default {
    
    // validate(data){
    //     // console.log(data.params);
    //     // return [1,2,3,4].includes(data.params.pid);
    //     // return data.params.pid ==
    // }
    validate(data){
        console.log(data.params.pid);
        // return data.params.pid == 1 || data.params.pid == 2;
        // return ['1','2','3','4','5'].includes(data.params.pid);

        // regex test to check if the pid is integer
        return /^\d+$/.test(data.params.pid);
    }
}
</script>
