<script setup>
import InitAll from '../components/InitAll.vue';
import StakingTest from '../components/StakingTest.vue';
import InitVer2 from '../components/InitGamify.vue'
import InitTtg from '../components/InitTTG.vue'
import FullPool from '../components/FullPool.vue'
import OldPool from '../components/OldPool.vue'
</script>

<template>
    <div class="md:hero mx-auto p-4">
        <div class="md:hero-content flex flex-col">
            <h1 class="text-center text-5xl md:pl-12 font-bold text-transparent bg-clip-text bg-gradient-to-tr from-[#9945FF] to-[#14F195]">
          Staking Pool
        </h1>
            <!-- mainnet
            <div class="text-center">
                <old-pool></old-pool>
            </div> -->
            舊合約轉新合約
            <div class="text-center">
                <init-all></init-all>
            </div>
            <!-- <div class="text-center">
                <staking-test></staking-test>
            </div> -->
            <!-- TTG
            <div class="text-center">
                <init-ttg></init-ttg>
            </div>
            Gamify
            <div class="text-center">
                <init-ver2></init-ver2>
            </div>
            Addition
            <div class="text-center">
                <full-pool></full-pool>
            </div> -->
      </div>
    </div>
</template>