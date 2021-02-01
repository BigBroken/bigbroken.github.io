<template>
    <div class="section">
        <div >
            <h2> About Me: </h2>
            <div class="bio">
            <div class="flex-40">
                <img src='../assets/bioCover.jpg'>
            </div>
            <div class="flex-60">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras commodo erat at tellus rutrum, vitae volutpat risus varius. Nullam dictum augue non consequat ultricies. Nam facilisis nunc sit amet dolor porttitor molestie. Pellentesque pellentesque est vel magna mollis, et fermentum sem pharetra. Vivamus posuere pretium lacinia. Cras eget libero in libero egestas cursus ac vitae leo. Sed convallis, felis non tincidunt convallis, mi nisi malesuada libero, in laoreet augue nisi eu tortor. Vestibulum vitae turpis dolor. Sed sagittis arcu non accumsan commodo. Nullam sollicitudin ultrices nunc at vulputate. Mauris sit amet risus in augue condimentum condimentum id quis nunc. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Nullam sit amet nisi eget orci consectetur faucibus ac eget elit. Maecenas dignissim pharetra ligula quis fermentum. Fusce id rhoncus lacus, sed consequat ex.

Duis eleifend maximus felis non tristique. Praesent rhoncus pretium accumsan. Donec turpis magna, imperdiet ac interdum nec, tincidunt vitae urna. In lacinia mauris ex, eu faucibus lectus aliquet ac. Morbi ut felis lorem. Sed id libero nisi. Donec volutpat velit in felis vestibulum, nec tincidunt augue tincidunt. Mauris pretium, justo tincidunt ultrices pellentesque, est tellus posuere mi, id vestibulum elit dui at ligula. Cras vitae erat at purus imperdiet porta at et ligula. Integer at felis tortor. Integer eget gravida augue. Phasellus dapibus lorem eros, et condimentum sapien commodo et. Donec at metus id dolor dignissim rhoncus. Duis et tellus libero. Phasellus mattis luctus consequat.

Nullam tempor ante ac sodales pulvinar. Nam vel urna mattis, dictum lectus non, lobortis eros. Interdum et malesuada fames ac ante ipsum primis in faucibus. Suspendisse vulputate vulputate quam ut semper. Etiam non libero purus. Etiam porta ipsum aliquet auctor consectetur. Aliquam sapien augue, commodo vitae tellus eu, cursus semper tellus.
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