<template>
    <div class="row">
        <div class="col s3">
            <ul class="collection with-header">
                <li class="collection-header">
                    <h4>Resources</h4>
                </li>
                <li><a class="collection-item" v-on:click="changeTab('how')">
                        How to stop the bleeing.</a>
                </li>
                <li><a class="collection-item" v-on:click="changeTab('stop')">
                        Stop the bleed videos</a>
                </li>
                <li><a class="collection-item" v-on:click="changeTab('flow')">
                        Flowchart</a>
                </li>
                <li><a class="collection-item" v-on:click="changeTab('Links')">
                        External Links</a>
                </li>
            </ul>
        </div>
        <div class="col s9">
            <div>
                <div v-if="currentTab == 'how'">
                    <HowToStop />
                </div>
                <div v-if="currentTab == 'stop'">
                    <StopVideo />
                </div>
                <div v-if="currentTab == 'flow'">
                    <div id="img">
                        <img src="./images/flowchat.png">    
                    </div>                    
                </div>
                <div v-if="currentTab == 'Links'">
                    <Links />
                </div>
            </div>
        </div>
    </div>
</template>
<script>
import HowToStop from './learn/Howtostop.vue'
import StopVideo from './learn/Stopvideo.vue'
import Links from './learn/Links.vue'

export default {
    name: 'Learn',
    components: {
        HowToStop,
        StopVideo,
        Links
    },
    data: function() {
        return {
            currentTab: 'how'
        }
    },
    props: {
        msg: String
    },
    methods: {
        changeTab: function(val) {
            this.currentTab = val;
        }
    }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.row {
    margin-top: 50px;
}

img {
    width: 400px;
    height: auto;
}

#img {
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>