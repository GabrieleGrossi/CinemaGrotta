<template>
    <div class="container mt-5">
        <div class="row">
            <h2 class="col-12 text-center mb-5">
                I Nostri film in programmazione
            </h2>

            <div class="d-flex flex-wrap ">
                <div class="col-4 text-center">                    
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQvii9Wp-FojdpH9ZZVQaaHsA4dIbtvOCkXUwg8C5xepnwWYzbE" alt=""> 
                    <h3 class="mb-5">
                        Talk to me 
                    </h3> 
                </div>
                <div class="col-4 text-center">
                    <img src="https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcTYmtbdBgdbAmsTuyzdoO7gXuTovN_afKWI1spSPcq-i2lTz3h-" alt="">
                    <h3 class="mb-5">
                        Napoleon
                    </h3>  
                </div>
                <div class="col-4 text-center">
                    <img src="https://pbs.twimg.com/media/FvUVt3hXgAAxP1H?format=jpg&name=900x900" alt=""> 
                    <h3 class="mb-5">
                        Oppheniemer
                    </h3> 
                </div>
                <div class="col-4 text-center">
                    <img src="https://dx35vtwkllhj9.cloudfront.net/universalstudios/the-exorcist-believer/images/regions/us/onesheet.jpg" alt=""> 
                    <h3 class="mb-5">
                        The exorcist 
                    </h3> 
                </div>
                <div class="col-4 text-center">
                    <img src="https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcQRRnrL3TtMpIBLn6ziIjEjzVvhZ3IKVg3H12AxyHHiQKAdG6vg" alt="">
                    <h3 class="mb-5">
                        Assasinio a Venezia
                    </h3>  
                </div>
                <div class="col-4 text-center">
                    <img src="https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcRNLr3NqxrphI_zJ6h7AuRaicAqZQ2k6Jnz287uq0PDkPKTQuUu" alt=""> 
                    <h3 class="mb-5">
                        Asteroid City
                    </h3> 
                </div>
                <div class="col-4 text-center">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSGLF6InMb-DljgyKSbKfrPFDqdxDLgI19pnJ55Lo0_bqMfXKZ4" alt=""> 
                    <h3 class="mb-5">
                        The Creator 
                    </h3> 
                </div>
                <div class="col-4 text-center">
                    <img src="https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcTmA9ge0Gu2orRtsGm1T-lOQAuyg2W0Dt3RMuO3lxFLpHD5Y-kp" alt="">
                    <h3 class="mb-5">
                        Io Capitano
                    </h3>  
                </div>
                <div class="col-4 text-center">
                    <img src="https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcRObMnNWPtLL7RFRL2kRHPUviAd3SdXX1ThfWkpWSEMV3rJbW-d" alt=""> 
                    <h3 class="mb-5">
                        The Palace
                    </h3> 
                </div>
                <div class="col-4 text-center">
                    <img src="https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcQMF85NA2pN5p_bVhW-eodoEKagJwKqjqjq_3QFj15fVeaL-9bC" alt=""> 
                    <h3 class="mb-5">
                        The Nun II 
                    </h3>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'Film'
}
</script>
<style lang="scss" scoped>
img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    padding: 1.5rem;
    margin: 1rem;

    &:hover{
        transform: scale(1.05);
    }
}

</style>