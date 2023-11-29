<script setup>
import {useNumbersStore} from "../stores/numbers"
const {numbers,doubleNumber,filterNum} =useNumbersStore()
</script>

<template>
    <div>
        <h1>GreatGrandChild Component {{ filterNum(20) }}</h1>
        
    </div>
</template>