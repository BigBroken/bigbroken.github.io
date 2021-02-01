<template>
    <div class="section">
        <div >
            <h2> About Me: </h2>
            <div class="bio">
            <div class="flex-40">
                <img src='../assets/bioCover.jpg'>
            </div>
            <div class="flex-60">
                <p>I am an isotope geochemist who seeks to understand the co-evolution of interlinked cryospheric, geologic, biologic, and oceanographic systems. My research centers on the the application of geochemical tools to extend our record of Antarctic Ice Sheet change into the recent geologic past using presently ice covered archives.

                I am currently (beginning February, 2021) a postdoctoral fellow at Tulane University working to understand the recent history of the Thwaites-Pine Island glacier system as part of the International Thwaites Glacier Collaboration. I recently completed my Ph.D. at the University of South Florida (January, 2021) where I worked to reconstruct Holocene grounding line history in the southern Ross Sea Embayment as part of the Subglacial Antarctic Lakes Scientific Access (SALSA) Project.

                Click the buttons below to get in contact via email and twitter, or keep scrolling to learn more about what I'm currently working on!
                </p>
            </div>
            </div>
        </div>
    </div>
</template>

<script>
  export default {}
</script>

<style scoped>

@media (min-width: 768px){
    .section{
        max-width: 720px;
    }
}
@media (min-width: 992px){
    .section{
        max-width: 960px;
    }
}
@media (min-width: 1200px){
    .section{
        max-width: 1140px;
    }
}


    .section{
        width: 100%;
        padding-right: 0.75rem;
        padding-left: 0.75rem;
        margin-right: auto;
        margin-left: auto;
    }
    h2{
        text-align: left;
    }
    .bio {
        display:flex;
    }
    .flex-40 {
        flex: 0 0 41.6666666667%;
        max-width: 41.6666666667%;
    }
    .flex-60 {
        padding-left:2em;  
        flex: 0 0 58.3333333333%;
        max-width: 58.3333333333%;
    }
    img {
        max-width: 100%;
        height: auto;
    }
</style>