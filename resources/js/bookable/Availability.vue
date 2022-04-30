<template>
    <div>
        <h6 class="text-uppercase text-secondary fw-bolder">Check Availability</h6>
        <div class="form-horizontal row mb-1">
            <div class="form-group col-md-6">
                <label for="from">From</label>
                <input
                    id="from"
                    type="text"
                    name="from"
                    class="form-control form-control-sm"
                    placeholder="Star Date"
                    v-model="from"
                >
            </div>
            <div class="form-group col-md-6">
                <label for="to">To</label>
                <input
                    id="to"
                    type="text"
                    name="to"
                    class="form-control form-control-sm"
                    placeholder="End Date"
                    v-model="to"
                    @keyup="check"
                >
            </div>
        </div>
        <button class="btn btn-secondary w-100" @click="check">Check!</button>
    </div>
</template>

<script>
export default {
    data(){
        return {
            from: null,
            to: null
        }
    },
    methods: {
        check(){

        }
    }
}
</script>

<style scoped>
    label{
        font-size: 0.7rem;
        text-transform: uppercase;
        color: gray;
        font-weight: bolder;
    }
</style>
