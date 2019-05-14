<template>
    <div class="row">
        <h1>Stop The Bleed Video</h1>
        <form action="#">
            <div class="file-field input-field" red accent-4>
                <div class="btn  red darken-4">
                    <span>Upload your own video</span>
                    <input type="file">
                </div>
                <div class="file-path-wrapper">
                    <input class="file-path validate" type="text">
                </div>
            </div>
        </form>
        <h3>How to Use a Tourniquet</h3>
        <p>In this video, Dr. Lenworth Jacobs walks you through how to apply a tourniquet on a bleeding victim. Lenworth M. Jacobs, MD, MPH, FACS, is a trauma surgeon and Chair of the Hartford Consensus, a committee that aims to create a protocol for national policy to enhance survivability from active shooter and intentional mass casualty events.</p>
        <div class="video-container"><iframe src="https://youtube.com/embed/y81aJ81ln5Q" allowfullscreen width="640" height="360" frameborder="0" title="Hartford Consensus: How to Use a Tourniquet"></iframe></div>
        <p>&nbsp;</p>
        <h3>Improving Survivability</h3>
        <p>This brief video produced by the Hartford Consensus provides an overview of recommended response and bleeding control protocol in the event of a mass casualty event. The video, in conjunction with other training materials, can be useful as an introduction or refresher to bleeding control training.</p>
        <div class="video-container"><iframe src="https://youtube.com/embed/Yv7Fzyb2CFo" allowfullscreen width="640" height="360" frameborder="0" title="The Hartford Consensus: Improving Survivability"></iframe></div>
        <p>&nbsp;</p>
        <h3>See Stop the Bleed</h3>
        <p>How can you stop the bleed? Learn about Stop the Bleed kits that are popping up in public sites across the nation and on TV's Code Black!</p>
        <div class="video-container"><iframe src="https://youtube.com/embed/mnmYymGuRO0" allowfullscreen width="640" height="360" frameborder="0" title="See hot to Stop the Bleed"></iframe></div>
        <p>&nbsp;</p>
        <h3>The Cast of 'Code Black' on Stop The Bleed</h3>
        <p>The cast of 'Code Black' and CBS Cares encourage you to learn how to stop the bleed.</p>
        <div class="video-container"><iframe src="https://youtube.com/embed/ZIvl5qh-cGQ" allowfullscreen width="640" height="360" frameborder="0" title="The Cast of Code Black on Stop the Bleed"></iframe></div>
        <p>&nbsp;</p>
        <h3>A Perfect Stranger</h3>
        <p>"A Perfect Stranger" tells the story of Kinneil and Angelia and the event that brought the two women together. It is a powerful reminder that at a moment's notice, any one of us might find ourselves in a situation where we are the help until help arrives. In the end, this film calls on all Americans to remake what it means to be a bystander. <em>Video courtesy of FEMA.</em></p>
        <div><iframe src="https://youtube.com/embed/qBrMU0sLoHQ" allowfullscreen width="640" height="360" frameborder="0" title="A Perfect Stranger"></iframe></div>
        <p>&nbsp;</p>
    </div>
</template>
<script>
export default {
    name: 'StopVideo',
    props: {
        msg: String
    }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>