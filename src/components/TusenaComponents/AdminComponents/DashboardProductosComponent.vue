<template>
  <!-- <svg xmlns="http://www.w3.org/2000/svg" style="display: none;">
      <symbol id="check2" viewBox="0 0 16 16">
        <path d="M13.854 3.646a.5.5 0 0 1 0 .708l-7 7a.5.5 0 0 1-.708 0l-3.5-3.5a.5.5 0 1 1 .708-.708L6.5 10.293l6.646-6.647a.5.5 0 0 1 .708 0z"/>
      </symbol>
      <symbol id="circle-half" viewBox="0 0 16 16">
        <path d="M8 15A7 7 0 1 0 8 1v14zm0 1A8 8 0 1 1 8 0a8 8 0 0 1 0 16z"/>
      </symbol>
      <symbol id="moon-stars-fill" viewBox="0 0 16 16">
        <path d="M6 .278a.768.768 0 0 1 .08.858 7.208 7.208 0 0 0-.878 3.46c0 4.021 3.278 7.277 7.318 7.277.527 0 1.04-.055 1.533-.16a.787.787 0 0 1 .81.316.733.733 0 0 1-.031.893A8.349 8.349 0 0 1 8.344 16C3.734 16 0 12.286 0 7.71 0 4.266 2.114 1.312 5.124.06A.752.752 0 0 1 6 .278z"/>
        <path d="M10.794 3.148a.217.217 0 0 1 .412 0l.387 1.162c.173.518.579.924 1.097 1.097l1.162.387a.217.217 0 0 1 0 .412l-1.162.387a1.734 1.734 0 0 0-1.097 1.097l-.387 1.162a.217.217 0 0 1-.412 0l-.387-1.162A1.734 1.734 0 0 0 9.31 6.593l-1.162-.387a.217.217 0 0 1 0-.412l1.162-.387a1.734 1.734 0 0 0 1.097-1.097l.387-1.162zM13.863.099a.145.145 0 0 1 .274 0l.258.774c.115.346.386.617.732.732l.774.258a.145.145 0 0 1 0 .274l-.774.258a1.156 1.156 0 0 0-.732.732l-.258.774a.145.145 0 0 1-.274 0l-.258-.774a1.156 1.156 0 0 0-.732-.732l-.774-.258a.145.145 0 0 1 0-.274l.774-.258c.346-.115.617-.386.732-.732L13.863.1z"/>
      </symbol>
      <symbol id="sun-fill" viewBox="0 0 16 16">
        <path d="M8 12a4 4 0 1 0 0-8 4 4 0 0 0 0 8zM8 0a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-1 0v-2A.5.5 0 0 1 8 0zm0 13a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-1 0v-2A.5.5 0 0 1 8 13zm8-5a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1 0-1h2a.5.5 0 0 1 .5.5zM3 8a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1 0-1h2A.5.5 0 0 1 3 8zm10.657-5.657a.5.5 0 0 1 0 .707l-1.414 1.415a.5.5 0 1 1-.707-.708l1.414-1.414a.5.5 0 0 1 .707 0zm-9.193 9.193a.5.5 0 0 1 0 .707L3.05 13.657a.5.5 0 0 1-.707-.707l1.414-1.414a.5.5 0 0 1 .707 0zm9.193 2.121a.5.5 0 0 1-.707 0l-1.414-1.414a.5.5 0 0 1 .707-.707l1.414 1.414a.5.5 0 0 1 0 .707zM4.464 4.465a.5.5 0 0 1-.707 0L2.343 3.05a.5.5 0 1 1 .707-.707l1.414 1.414a.5.5 0 0 1 0 .708z"/>
      </symbol>
    </svg> -->






  <!-- <div class="dropdown position-fixed bottom-0 end-0 mb-3 me-3 bd-mode-toggle">
      <button class="btn btn-bd-primary py-2 dropdown-toggle d-flex align-items-center" id="bd-theme" type="button"
        aria-expanded="false" data-bs-toggle="dropdown" aria-label="Toggle theme (auto)">
        <svg class="bi my-1 theme-icon-active" width="1em" height="1em">
          <use href="#circle-half"></use>
        </svg>
        <span class="visually-hidden" id="bd-theme-text">Toggle theme</span>
      </button>
      <ul class="dropdown-menu dropdown-menu-end shadow" aria-labelledby="bd-theme-text">
        <li>
          <button type="button" class="dropdown-item d-flex align-items-center" data-bs-theme-value="light"
            aria-pressed="false">
            <svg class="bi me-2 opacity-50 theme-icon" width="1em" height="1em">
              <use href="#sun-fill"></use>
            </svg>
            Light
            <svg class="bi ms-auto d-none" width="1em" height="1em">
              <use href="#check2"></use>
            </svg>
          </button>
        </li>
        <li>
          <button type="button" class="dropdown-item d-flex align-items-center" data-bs-theme-value="dark"
            aria-pressed="false">
            <svg class="bi me-2 opacity-50 theme-icon" width="1em" height="1em">
              <use href="#moon-stars-fill"></use>
            </svg>
            Dark
            <svg class="bi ms-auto d-none" width="1em" height="1em">
              <use href="#check2"></use>
            </svg>
          </button>
        </li>
        <li>
          <button type="button" class="dropdown-item d-flex align-items-center active" data-bs-theme-value="auto"
            aria-pressed="true">
            <svg class="bi me-2 opacity-50 theme-icon" width="1em" height="1em">
              <use href="#circle-half"></use>
            </svg>
            Auto
            <svg class="bi ms-auto d-none" width="1em" height="1em">
              <use href="#check2"></use>
            </svg>
          </button>
        </li>
      </ul>
    </div> -->






  <main class="col-md-9 ms-sm-auto col-lg-10 px-md-4">
    <div class="d-flex justify-content-between flex-wrap flex-md-nowrap align-items-center pt-3 pb-2 mb-3 border-bottom">
      <h2 class="">Panel de Administracion</h2> <button type="button" class="custom-btn btn-register my-2"
        data-bs-toggle="modal" data-bs-target="#registrarProductoModal"> <i class="bi bi-plus-lg"></i> Agregar
        Producto</button>


      <div class="btn-toolbar mb-2 mb-md-0">
        <div class="btn-group me-2">
          <button type="button" class="btn btn-sm btn-outline-secondary"> Compartir</button>
          <button type="button" class="btn btn-sm btn-outline-secondary">Exportar</button>
        </div>
        <button type="button" class="btn btn-sm btn-outline-secondary dropdown-toggle">
          <span data-feather="calendar" class="align-text-bottom"></span>
          Esta Semana
        </button>
      </div>
    </div>

    <!-- <canvas class="my-4 w-100" id="myChart" width="900" height="380"></canvas> -->

    <h3>Productos</h3>
    <div class="table-responsive">
      <table class="table table-striped table-hover table-sm ">
        <thead class="table-success text-start">
          <tr class="me-4">
            <th scope="col ">#</th>
            <th scope="col">Titulo</th>
            <!-- <th scope="col">Autor(es)</th> -->
            <th scope="col">Autor</th>
            <th scope="col">A&ntilde;o</th>
            <th scope="col">Linea Programatica</th>
            <th scope="col">Detalle</th>

            <th scope="col">Tipo</th>
            <th scope="col">Subtipo</th>
            <th scope="col">URL</th>

            <th scope="col">Idioma</th>
            <th scope="col">Imagen</th>
            <th scope="col">Acciones</th>

          </tr>
        </thead>
        <tbody class="table-group-divider text-start">
          <tr v-for="(producto, index) in productos" :key="index" class="align-middle">


            <td>{{ producto.producto_id }}</td>
            <td>{{ producto.productos_titulo }}</td>
            <td>{{ producto.productos_autor }}</td>

            <td>{{ producto.productos_ano }}</td>
            <td>{{ producto.productos_linea }}</td>
            <td>{{ producto.productos_detalle }}</td>
            <td>{{ producto.productos_tipo }}</td>
            <td>{{ producto.productos_subtipo }}</td>
            <td>{{ producto.productos_url }}</td>
            <td>{{ producto.productos_idioma }}</td>
            <td>{{ producto.productos_imagen }}</td>






            <td class="d-flex text-start">
              <div class="row text-start">
                <div class="col text-start">
                  <button class="btn btn-warning  me-2" data-bs-toggle="modal" data-bs-target="#actualizarProductoModal"
                    @:click="buscarProducto(producto.producto_id)">
                    <i class="bi bi-pencil-square"></i></button>
                  <button class="btn btn-danger" data-bs-toggle="modal" data-bs-target="#eliminarProductoModal"
                    @:click="buscarProducto(producto.producto_id)"> <i class="bi bi-trash3-fill"></i></button>



                </div>

              </div>


            </td>

          </tr>

        </tbody>
      </table>
    </div>
  </main>


  <div class="modal fade" id="registrarProductoModal" tabindex="-1" aria-labelledby="exampleModalLabel"
    data-bs-backdrop="static" data-bs-keyboard="false" aria-hidden="true">
    <div class="modal-dialog modal-lg rounded rounded-5">
      <div class="modal-content row mx-2 me-2 bg-dark">
        <!-- <div class="modal-header border border-0 d-flex justify-content-end p-2 pt-2 pe-2 m-0">
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div> -->
        <!-- <div class="modal-header p-0 m-0 border border-0">
                    <img src="https://placeimg.com/600/200/animals" class="img-fluid  mx-auto d-block" alt="...">
                </div> -->
        <div class="modal-body py-0 mt-0 col-12 px-2">
          <div class="form-body p-0">
            <div class="row">
              <div class="form-holder p-0">
                <div class="form-content p-0 m-0">
                  <div class="form-items">
                    <h3>Agrega un Producto</h3>
                    <p>Llena los campos que veras a continuacion:</p>

                    <form class="" method="POST" v-on:submit.prevent="registrarProducto">

                      <div class="col-md-12">
                        <input class="form-control text-dark" type="text" required placeholder="Titulo" v-model="titulo">
                        <!-- <div class="valid-feedback">Username field is valid!</div>
                        <div class="invalid-feedback">Username field cannot be blank!</div> -->
                      </div>
                      <div class="col-md-12">
                        <input class="form-control text-dark" type="text" name="name" placeholder="Autor" v-model="autor"
                          required>
                        <!-- <div class="valid-feedback">Username field is valid!</div>
                        <div class="invalid-feedback">Username field cannot be blank!</div> -->
                      </div>

                      <div class="col-md-12">
                        <input class="form-control text-dark" type="date" name="apellido" placeholder="Año" v-model="ano"
                          required>
                        <!-- <div class="valid-feedback">Username field is valid!</div>
                        <div class="invalid-feedback">Username field cannot be blank!</div> -->
                      </div>


                      <div class="col-md-12">
                        <input class="form-control text-dark" type="text" name="" placeholder="Linea Programatica"
                          v-model="linea" required>
                        <!-- <div class="valid-feedback">Email field is valid!</div>
                        <div class="invalid-feedback">Email field cannot be blank!</div> -->
                      </div>


                      <div class="col-md-12">
                        <input class="form-control text-dark" type="text" name="" placeholder="Detalle" v-model="detalle"
                          required>
                        <!-- <div class="valid-feedback">Contrase&ntilde;a Valida!</div>
                        <div class="invalid-feedback">Contrase&ntilde;a sin llenar!</div> -->
                      </div>


                      <!-- <div class="col-md-12">
                        <input class="form-control text-dark" type="text" name="" placeholder="Tipo" v-model="tipo"
                          required>
                      </div> -->

                      <div class="col-md-12 text-dark">
                        <select name="subtipo" class="text-dark" v-model="tipo">
                          <option value="value1" selected disabled>Elija un Tipo de Producto</option>
                          <option value="Actividades como Evaluador">Actividades como Evaluador</option>
                          <option value="Apropiación Social del Conocimiento y Divulgación Pública de la Ciencia">
                            Apropiación Social del Conocimiento y Divulgación Pública de la Ciencia</option>
                          <option value="Desarrollo Tecnologico e Innovacion">Desarrollo Tecnológico e Innovación</option>
                          <option value="Formación de Recurso Humano para la CTEI">Formación de Recurso Humano para la
                            CTEI</option>
                          <option value="Generación de Nuevo Conocimiento">Generación de Nuevo Conocimiento</option>

                        </select>
                      </div>



                      <!-- <div class="col-md-12">
                        <input class="form-control text-dark" type="text" name="" placeholder="Subtipo" v-model="subtipo"
                          required>
                      </div> -->

                      <div class="col-md-12 text-dark">

                        <select name="subtipo" class="text-dark" v-model="subtipo">
                          <option value="value1" disabled>Elija un Subtipo de Producto</option>
                          <option value="Artículos de Investigación A1, A2, B y C">Artículos de Investigación A1, A2, B y
                            C</option>
                          <option value="Consultorías Científico-Tecnológicas">Consultorías Científico-Tecnológicas
                          </option>
                          <option value="Direcciones de Trabajo de Pregrado">Direcciones de Trabajo de Pregrado</option>
                          <option value="Divulgación Pública de la CTeI">Divulgación Pública de la CTeI</option>
                          <option value="Estrategias Pedagógicas para el
                            Fomento a la CTI">Estrategias Pedagógicas para el
                            Fomento a la CTI</option>
                          <option value="Eventos Científicos con Componente de Apropiación">Eventos Científicos con
                            Componente de Apropiación</option>
                          <option value="Informes Finales de Investigación">Informes Finales de Investigación</option>
                          <option value="Informes Técnicos">Informes Técnicos</option>
                          <option value="Normas Técnicas">Normas Técnicas</option>
                          <option value="Otro Programa Académico">Otro Programa Académico</option>
                          <option value="Participación en Comités de Evaluación">Participación en Comités de Evaluación
                          </option>
                          <option value="Plantas Piloto">Plantas Piloto</option>
                          <option
                            value="Procesos de Apropiación Social del Conocimiento para el Fortalecimiento o Solución de Asuntos de Interés Social">
                            Procesos de Apropiación Social del Conocimiento para el Fortalecimiento o Solución de Asuntos
                            de Interés Social</option>
                          <option value="Prototipos Industriales">Prototipos Industriales</option>
                          <option value="Proyectos de Investigacion y Desarrollo">Proyectos de Investigacion y Desarrollo
                          </option>
                          <option value="Proyectos de Investigación, Desarrollo e Innovación (ID+I)">Proyectos de
                            Investigación, Desarrollo e Innovación (ID+I)</option>

                        </select>

                      </div>


                      <div class="col-md-12">
                        <input class="form-control text-dark" type="text" name="" placeholder="URL/Documentacion"
                          v-model="url" required>
                      </div>
                      <div class="col-md-12">
                        <input class="form-control text-dark" type="text" name="" placeholder="Idioma" v-model="idioma"
                          required>
                      </div>
                      <div class="col-md-12">
                        <input class="form-control text-dark" type="text" name="" placeholder="Imagen" v-model="imagen"
                          required>
                      </div>


                      <div class="form-button mt-3 align-items-center d-flex justify-content-between">
                        <!-- <button id="submit" type="submit" class="btn btn-primary">Register</button> -->
                        <button type="submit" class="bg-dark p-0 m-0 border border-0" data-bs-dismiss="modal"
                          aria-label="Close">

                          <a class="border border-light mt-0">
                            <span></span>
                            <span></span>
                            <span></span>
                            <span></span>
                            Registrar
                          </a>

                        </button>


                        <button type="button" class="btn btn-cerrar border border-danger" data-bs-dismiss="modal"
                          aria-label="Close">Cancelar</button>

                      </div>

                    </form>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>



  <!-- MODAL ACTUALIZAR MODAL ACTUALIZAR MODAL ACTUALIZAR MODAL ACTUALIZAR MODAL ACTUALIZAR MODAL ACTUALIZAR MODAL ACTUALIZAR MODAL ACTUALIZAR MODAL ACTUALIZAR MODAL ACTUALIZAR MODAL ACTUALIZAR MODAL ACTUALIZAR  -->


  <div class="modal fade" id="actualizarProductoModal" tabindex="-1" aria-labelledby="exampleModalLabel"
    data-bs-backdrop="static" data-bs-keyboard="false" aria-hidden="true">
    <div class="modal-dialog modal-lg rounded rounded-5">
      <div class="modal-content row mx-2 me-2 bg-dark">
        <!-- <div class="modal-header border border-0 d-flex justify-content-end p-2 pt-2 pe-2 m-0">
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div> -->
        <!-- <div class="modal-header p-0 m-0 border border-0">
                    <img src="https://placeimg.com/600/200/animals" class="img-fluid  mx-auto d-block" alt="...">
                </div> -->
        <div class="modal-body py-0 mt-0 col-12 px-2">
          <div class="form-body p-0">
            <div class="row">
              <div class="form-holder p-0">
                <div class="form-content p-0 m-0">
                  <div class="form-items">
                    <h3>Actualiza un Funcionario</h3>
                    <p>Llena los campos que veras a continuacion:</p>

                    <form class="" method="POST" v-on:submit.prevent="actualizarProducto(producto.producto_id)">

                      <div class="col-md-12">
                        <input class="form-control text-dark" type="text" required v-model="producto.productos_titulo">
                        <!-- <div class="valid-feedback">Username field is valid!</div>
                        <div class="invalid-feedback">Username field cannot be blank!</div> -->
                      </div>
                      <div class="col-md-12">
                        <input class="form-control text-dark" type="text" name="name" v-model="producto.productos_autor"
                          required>
                        <!-- <div class="valid-feedback">Username field is valid!</div>
                        <div class="invalid-feedback">Username field cannot be blank!</div> -->
                      </div>

                      <div class="col-md-12">
                        <input class="form-control text-dark" type="text" name="apellido"
                          v-model="producto.productos_linea" required>
                        <!-- <div class="valid-feedback">Username field is valid!</div>
                        <div class="invalid-feedback">Username field cannot be blank!</div> -->
                      </div>


                      <div class="col-md-12">
                        <input class="form-control text-dark" type="text" name="" v-model="producto.productos_detalle"
                          required>
                        <!-- <div class="valid-feedback">Email field is valid!</div>
                        <div class="invalid-feedback">Email field cannot be blank!</div> -->
                      </div>


                      <div class="col-md-12">
                        <input class="form-control text-dark" type="text" name="" v-model="producto.productos_tipo"
                          required>
                        <!-- <div class="valid-feedback">Contrase&ntilde;a Valida!</div>
                        <div class="invalid-feedback">Contrase&ntilde;a sin llenar!</div> -->
                      </div>


                      <div class="col-md-12">
                        <input class="form-control text-dark" type="text" name="" v-model="producto.productos_subtipo"
                          required>
                      </div>
                      <div class="col-md-12">
                        <input class="form-control text-dark" type="text" name="" v-model="producto.productos_idioma"
                          required>
                      </div>

                      <div class="form-check mt-2">
                        <input class="form-check-input" type="checkbox" value='' id="invalidCheck">
                        <label class="form-check-label">El usuario sera Administrador?</label>
                        <!-- <div class="invalid-feedback">Tenga en cuenta que el administrador podra ver, modificar o eliminar los datos contenidos en la base de datos de la aplicacion</div> -->
                      </div>


                      <div class="form-button mt-3 align-items-center d-flex justify-content-between">
                        <!-- <button id="submit" type="submit" class="btn btn-primary">Register</button> -->
                        <button type="submit" class="bg-dark p-0 m-0 border border-0" data-bs-dismiss="modal"
                          aria-label="Close">

                          <a class="border border-light mt-0">
                            <span></span>
                            <span></span>
                            <span></span>
                            <span></span>
                            Actualizar
                          </a>

                        </button>


                        <button type="button" class="btn btn-cerrar border border-danger" data-bs-dismiss="modal"
                          aria-label="Close">Cancelar</button>

                      </div>

                    </form>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>








  <div class="modal fade" id="eliminarProductoModal" tabindex="-1" aria-labelledby="exampleModalLabel"
    data-bs-backdrop="static" data-bs-keyboard="false" aria-hidden="true">
    <div class="modal-dialog modal-lg rounded rounded-5">
      <div class="modal-content row mx-2 me-2 bg-dark">
        <!-- <div class="modal-header border border-0 d-flex justify-content-end p-2 pt-2 pe-2 m-0">
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div> -->
        <!-- <div class="modal-header p-0 m-0 border border-0">
                    <img src="https://placeimg.com/600/200/animals" class="img-fluid  mx-auto d-block" alt="...">
                </div> -->
        <div class="modal-body py-0 mt-0 col-12 px-2">
          <div class="form-body p-0">
            <div class="row">
              <div class="form-holder p-0">
                <div class="form-content p-0 m-0">
                  <div class="form-items">
                    <h3>Seguro deseas eliminar el producto: {{ producto.productos_titulo }}?</h3>


                    <form class="" method="POST" v-on:submit.prevent="eliminarProducto(producto.producto_id)">



                      <div class="form-button mt-5 align-items-center d-flex justify-content-between">
                        <!-- <button id="submit" type="submit" class="btn btn-primary">Register</button> -->
                        <button type="submit" class="bg-dark p-0 m-0 border border-0" data-bs-dismiss="modal"
                          aria-label="Close">

                          <a class="border border-light mt-0">
                            <span></span>
                            <span></span>
                            <span></span>
                            <span></span>
                            Eliminar
                          </a>

                        </button>


                        <button type="button" class="btn btn-cerrar border border-danger" data-bs-dismiss="modal"
                          aria-label="Close">Cancelar</button>

                      </div>

                    </form>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>




<script>

export default {

  name: "DashboardProductosComponent",

  data() {
    return {
      producto: [],
      productos: [],

      id: null,
      titulo: '',
      autor: "",
      ano: "",
      linea: "",
      detalle: "",
      tipo: "",
      subtipo: "Elija un Subtipo de Producto",
      url: "",
      idioma: "",
      imagen: "",


    }
  },


  async mounted() {
    await this.buscarProductos();

  },


  methods: {

    async buscarProductos() {

      await this.axios.get('http://localhost:3000/producto')
        .then(response => {
          console.log(response);
          this.productos = response.data.new_producto
          // console.log(response.data.new_funcionario[0].funcionario_id);
          // console.log(response.data.new_producto);
          // console.log(this.funcionarios);
          // console.log(this.state.productos);
        }) //Mostrar por consola el error
        .catch((e) => {
          console.log(e)
        });
    },

    async registrarProducto() {

      let json = {

        // "funcionario_iden": this.identificacion,
        // "funcionario_nombre": this.nombres,
        // "funcionario_apellido": this.apellidos,
        // "funcionario_correo": this.correo,
        // "funcionario_contraseña": this.contrasena,
        // "funcionario_telefono": this.telefono,
        // "funcionario_administrador": this.admin,



        "productos_titulo": this.titulo,
        "productos_ano": this.ano,
        "productos_url": this.url,
        "productos_detalle": this.detalle,
        "productos_autor": this.autor,
        "productos_tipo": this.tipo,
        "productos_subtipo": this.subtipo,
        "productos_idioma": this.idioma,
        "productos_linea": this.linea,
        "producto_imagen": this.imagen,

      };
      await this.axios.post('http://localhost:3000/producto', json)
        .then(data => {
          console.log(data);
          alert(data.data.message)
          this.buscarProductos();


        })
    },


    async buscarProducto(producto_id) {
      console.log(producto_id);

      await this.axios.get('http://localhost:3000/producto/' + producto_id)
        .then(response => {
          this.producto = response.data.new_producto;

          console.log(this.producto);
          // console.log(response.data.new_funcionario[0].funcionario_id);
          // console.log(response.data.new_producto);
          // console.log(this.funcionarios);
          // console.log(this.state.productos);
        }) //Mostrar por consola el error
        .catch((e) => {
          console.log(e)
        });
    },


    async actualizarProducto(producto_id) {

      let json = {

        "productos_titulo": this.producto.productos_titulo,
        "productos_ano": this.producto.productos_ano,
        "productos_url": this.producto.productos_url,
        "productos_detalle": this.producto.productos_detalle,
        // "productos_autor": this.producto.productos_autor,
        "productos_tipo": this.producto.productos_tipo,
        "productos_subtipo": this.producto.productos_subtipo,
        "productos_idioma": this.producto.productos_idioma,
        "productos_linea": this.producto.productos_linea,
        "producto_imagen": this.producto.productos_imagen,


        // PRODUCTO.productos_titulo = productos_titulo
        // PRODUCTO.productos_ano = productos_ano
        // PRODUCTO.productos_url = productos_url
        // PRODUCTO.productos_detalle = productos_detalle
        // PRODUCTO.productos_tipo = productos_tipo
        // PRODUCTO.productos_subtipo = productos_subtipo
        // PRODUCTO.productos_idioma = productos_idioma
        // PRODUCTO.productos_linea = productos_linea
        // PRODUCTO.producto_imagen = producto_imagen

      };
      console.log(json);

      console.log(producto_id);
      console.log(this.producto);
      await this.axios.patch('http://localhost:3000/producto/' + producto_id, json)
        .then(response => {
          alert(response.data.message);
          // console.log(response.data.new_funcionario[0].funcionario_id);
          // console.log(response.data.new_producto);
          // console.log(this.funcionarios);
          // console.log(this.state.productos);
        }) //Mostrar por consola el error
        .catch((e) => {
          console.log(e)
        });

      this.buscarProductos();
    },




    async eliminarProducto(producto_id) {

      console.log(producto_id);
      await this.axios.delete('http://localhost:3000/producto/' + producto_id)
        .then(response => {
          console.log(response.data.message);
          alert(response.data.message);    // console.log(response.data.new_funcionario[0].funcionario_id);
          // console.log(response.data.new_funcionario[0].funcionario_id);
          // console.log(response.data.new_producto);
          // console.log(this.funcionarios);
          // console.log(this.state.productos);
        }) //Mostrar por consola el error
        .catch((e) => {
          console.log(e)
        });

      this.buscarProductos();
    },







  },


}
</script>

<style scoped>
.custom-btn {

  width: auto;
  height: 40px;
  color: #000000;
  border-radius: 5px;
  padding-inline: 10px;
  font-weight: 500;
  background: transparent;
  cursor: pointer;
  transition: all 0.1s ease;
  position: relative;
  display: inline-block;
  box-shadow: inset 2px 2px 2px 0px rgb(24, 183, 61),
    7px 7px 20px 0px rgba(0, 0, 0, .1),
    4px 4px 5px 0px rgba(0, 0, 0, .1);
  outline: none;
}

.btn-register {
  background: rgb(3, 187, 25);
  border: 1px;
  z-index: 1;

}













a {

  position: relative;
  display: inline-block;
  padding: 10px 20px;
  color: #09ff00;
  font-size: smaller;
  text-decoration: none;
  text-transform: uppercase;
  overflow: hidden;
  transition: .5s;
  margin-top: 40px;
  letter-spacing: 4px
}

a:hover {
  background: #09ff00;
  color: #000000;
  border-radius: 0px;
  box-shadow: 0 0 1px #09ff00,
    1 0 25px #09ff00,
    1 0 50px #09ff00,
    1 0 100px #09ff00;
}

a span {
  position: absolute;
  display: block;
}

a span:nth-child(1) {
  top: 0;
  left: -100%;
  width: 100%;
  height: 2px;
  background: linear-gradient(90deg, transparent, #09ff00);
  animation: btn-anim1 1s linear infinite;
}

@keyframes btn-anim1 {
  0% {
    left: -100%;
  }

  50%,
  100% {
    left: 100%;
  }
}

a span:nth-child(2) {
  top: -100%;
  right: 0;
  width: 2px;
  height: 100%;
  background: linear-gradient(180deg, transparent, #09ff00);
  animation: btn-anim2 1s linear infinite;
  animation-delay: .25s
}

@keyframes btn-anim2 {
  0% {
    top: -100%;
  }

  50%,
  100% {
    top: 100%;
  }
}

a span:nth-child(3) {
  bottom: 0;
  right: -100%;
  width: 100%;
  height: 2px;
  background: linear-gradient(270deg, transparent, #09ff00);
  animation: btn-anim3 1s linear infinite;
  animation-delay: .5s
}

@keyframes btn-anim3 {
  0% {
    right: -100%;
  }

  50%,
  100% {
    right: 100%;
  }
}

a span:nth-child(4) {
  bottom: -100%;
  left: 0;
  width: 2px;
  height: 100%;
  background: linear-gradient(360deg, transparent, #09ff00);
  animation: btn-anim4 1s linear infinite;
  animation-delay: .75s
}

@keyframes btn-anim4 {
  0% {
    bottom: -100%;
  }

  50%,
  100% {
    bottom: 100%;
  }

  /* @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;700;900&display=swap'); */
}













.btn-cerrar {

  position: relative;
  display: inline-block;
  padding: 10px 20px;
  color: #ff0000;
  font-size: smaller;
  text-decoration: none;
  text-transform: uppercase;
  overflow: hidden;
  transition: .5s;
  margin-top: 0px;
  letter-spacing: 4px;

}

.btn-cerrar:hover {
  background: #ff0000;
  color: #000000;
  border-radius: 0px;
  box-shadow: 0 0 1px #09ff00,
    1 0 25px #09ff00,
    1 0 50px #09ff00,
    1 0 100px #09ff00;
}

.btn-cerrar span {
  position: absolute;
  display: block;
}

.btn-cerrar span:nth-child(1) {
  top: 0;
  left: -100%;
  width: 100%;
  height: 2px;
  background: linear-gradient(90deg, transparent, #09ff00);
  animation: btn-anim1 1s linear infinite;
}

@keyframes btn-anim1 {
  0% {
    left: -100%;
  }

  50%,
  100% {
    left: 100%;
  }
}

a span:nth-child(2) {
  top: -100%;
  right: 0;
  width: 2px;
  height: 100%;
  background: linear-gradient(180deg, transparent, #09ff00);
  animation: btn-anim2 1s linear infinite;
  animation-delay: .25s
}

@keyframes btn-anim2 {
  0% {
    top: -100%;
  }

  50%,
  100% {
    top: 100%;
  }
}

a span:nth-child(3) {
  bottom: 0;
  right: -100%;
  width: 100%;
  height: 2px;
  background: linear-gradient(270deg, transparent, #09ff00);
  animation: btn-anim3 1s linear infinite;
  animation-delay: .5s
}

@keyframes btn-anim3 {
  0% {
    right: -100%;
  }

  50%,
  100% {
    right: 100%;
  }
}

a span:nth-child(4) {
  bottom: -100%;
  left: 0;
  width: 2px;
  height: 100%;
  background: linear-gradient(360deg, transparent, #09ff00);
  animation: btn-anim4 1s linear infinite;
  animation-delay: .75s
}

@keyframes btn-anim4 {
  0% {
    bottom: -100%;
  }

  50%,
  100% {
    bottom: 100%;
  }

  /* @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;700;900&display=swap'); */
}






imput {

  text-transform: uppercase;
}



*,
body {
  /* font-family: 'Poppins', sans-serif; */
  font-weight: 400;
  -webkit-font-smoothing: antialiased;
  text-rendering: optimizeLegibility;
  -moz-osx-font-smoothing: grayscale;
}

html,
body {
  height: 100%;
  background-color: #349adf;
  overflow: hidden;
}

/* .form-holder {} */

.form-holder .form-content {

  text-align: center;
  display: -webkit-box;
  display: -moz-box;
  display: -ms-flexbox;
  display: -webkit-flex;
  display: flex;
  -webkit-justify-content: center;
  justify-content: center;
  -webkit-align-items: center;
  align-items: center;
  max-width: 100%;
}

.form-content .form-items {
  border: 3px solid #0b6808;
  padding: 40px;
  display: inline-block;
  width: 100%;
  max-width: 100%;
  -webkit-border-radius: 10px;
  -moz-border-radius: 10px;
  border-radius: 10px;
  text-align: left;
  -webkit-transition: all 0.4s ease;
  transition: all 0.4s ease;
}

.form-content h3 {
  color: #fff;
  text-align: left;
  font-size: 28px;
  font-weight: 600;
  margin-bottom: 5px;
}

.form-content h3.form-title {
  margin-bottom: 30px;
}

.form-content p {
  color: #fff;
  text-align: left;
  font-size: 17px;
  font-weight: 300;
  line-height: 20px;
  margin-bottom: 30px;
}


.form-content label,
.was-validated .form-check-input:invalid~.form-check-label,
.was-validated .form-check-input:valid~.form-check-label {
  color: #fff;

}

.form-content input[type=text],
.form-content input[type=password],
.form-content input[type=email],
.form-content input[type=phone],
.form-content input[type=number],
.form-content input[type=date],

.form-content select {
  width: 100%;
  padding: 9px 20px;
  text-align: left;
  border: 0;
  outline: 0;
  border-radius: 6px;
  background-color: #fff;
  font-size: 15px;
  font-weight: 300;
  color: #8D8D8D;
  -webkit-transition: all 0.3s ease;
  transition: all 0.3s ease;
  margin-top: 16px;
}


.btn-primary {
  background-color: #7e7e7e;
  outline: none;
  border: 0px;
  box-shadow: none;
}

.btn-primary:hover,
.btn-primary:focus,
.btn-primary:active {
  background-color: #00b22c;
  outline: none !important;
  border: none !important;
  box-shadow: none;
}

.form-content textarea {
  position: static !important;
  width: 100%;
  padding: 8px 20px;
  border-radius: 6px;
  text-align: left;
  background-color: #fff;
  border: 0;
  font-size: 15px;
  font-weight: 300;
  color: #8D8D8D;
  outline: none;
  resize: none;
  height: 120px;
  -webkit-transition: none;
  transition: none;
  margin-bottom: 14px;
}

.form-content textarea:hover,
.form-content textarea:focus {
  border: 0;
  background-color: #ebeff8;
  color: #8D8D8D;
}

.mv-up {
  margin-top: -9px !important;
  margin-bottom: 8px !important;
}

.invalid-feedback {
  color: #ff606e;
}

.valid-feedback {
  color: #2acc80;
}
</style>