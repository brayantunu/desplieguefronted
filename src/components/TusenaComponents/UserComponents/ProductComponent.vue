<template>


<div class="container" v-if="productos.length == 0">

<h1>No se encontraron productos</h1>

</div>



    <div class="row justify-content-center mb-3" v-else v-for="(producto, index) in productos" :key="index">
        <div class="col-md-12">
            <div class="card shadow-0 border border-dark rounded-3" style="--bs-border-opacity: .5;">
                <div class="card-body">
                    <div class="row g-0">
                        <div class="col-xl-4 col-md-4 d-flex justify-content-center">
                            <div
                                class="bg-image hover-zoom ripple rounded ripple-surface me-md-3 mb-3 mb-md-0 d-flex justify-content-center">
                                <img src="https://picsum.photos/300/300" class="my-auto" style="width: 150px; height: 150px;" />
                                <a href="#!">
                                    <div class="hover-overlay">
                                        <div class="mask" style="background-color: rgba(253, 253, 253, 0.15);"></div>
                                    </div>
                                </a>
                            </div>
                        </div>

                        <div class="col-xl-6 col-md-5 col-sm-7 ">
                            <h5>{{ producto.productos_titulo }}</h5>
                            <div class="d-flex flex-row">
                                <div class="text-warning mb-1 me-2">
                                    <i class="fa fa-star"></i>
                                    <i class="fa fa-star"></i>
                                    <i class="fa fa-star"></i>
                                    <i class="fa fa-star"></i>
                                    <i class="fas fa-star-half-alt"></i>
                                    <span class="ms-1">
                                        3.7
                                    </span>
                                </div>
                                <span class="text-muted">{{ producto.producto_id }} vistas</span>
                            </div>

                            <!-- <p class="text mb-4 mb-md-0">
                                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Deleniti saepe
                                facere nostrum minima temporibus, asperiores quidem ad, aliquam distinctio
                                tenetur error totam sit facilis molestias architecto molestiae, quas
                                deserunt voluptatibus.
                            </p> -->


                            <div class="row w-100">
                                <div class="row">

                                    <div class="col-3">
                                        <h6>Tipo: </h6>
                                    </div>
                                    <div class="col-9">
                                        <h6> {{ producto.productos_tipo }}</h6>
                                    </div>
                                </div>
                            </div>


                            <div class="row w-100">
                                <div class="row">
                                    <div class="col-3">
                                        <h6>Subtipo: </h6>
                                    </div>
                                    <div class="col-9">
                                        <h6> {{ producto.productos_subtipo }}</h6>
                                    </div>
                                </div>
                            </div>


                            <div class="row w-100">
                                <div class="row">

                                    <div class="col-3">
                                        <h6>Detalle: </h6>
                                    </div>
                                    <div class="col-9">
                                        <h6> {{ producto.productos_detalle }}</h6>
                                    </div>
                                </div>
                            </div>


                            <div class="row w-100">
                                <div class="row">

                                    <div class="col-3">
                                        <h6>Codigo Proyecto: </h6>
                                    </div>
                                    <div class="col-9">
                                        <h6> {{ producto.productos_detalle }}</h6>
                                    </div>
                                </div>
                            </div>


                        </div>
                        <div class="col-xl-2 col-md-3 col-sm-5 my-auto text-end">
                            <!-- <div class="d-flex flex-row align-items-center mb-1">
                                                <h4 class="mb-1 me-1">$34,50</h4>
                                                <span class="text-danger"><s>$49.99</s></span>
                                            </div> -->
                            <!-- <h6 class="text-success">Free shipping</h6> -->
                            <div class="">
                                <button class="btn btn-secondary shadow-0 me-2 me-2 product-button" type="button">
                                    <router-link to="/productos/1" class="text-decoration-none text-light">ver
                                        mas </router-link> </button>
                                <a href="#!" class="btn btn-light border px-2 pt-2 icon-hover "><i
                                        class="fas fa-heart fa-lg px-1"></i></a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>







</template>

<script>
import { mapState, mapActions } from 'vuex';



export default {
    computed: {
        ...mapState({
            productos: 'productos',
        }),
    },

}


</script>

<style></style>