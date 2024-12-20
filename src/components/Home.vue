<template>
  <div class="home">
    <!-- Navegación -->
    <nav class="navbar">
      <div class="container">
        <div class="logo">
          <a href="#" class="navbar-brand">
            <img src="/src/assets/images/logo.png" alt="" />
          </a>
        </div>
        <div class="navbar-collapse">
          <ul class="navbar-nav nav">
            <li><a href="#home">Inicio</a></li>
            <li><a href="#services">Sevicios</a></li>
            <li><a href="#contact">Contacto</a></li>
            <li><a href="#testimonials">Testimonios</a></li>
          </ul>
        </div>
        <button class="cta-button">Únete Ahora</button>
      </div>
    </nav>

    <!-- Sección Hero -->
    <div id="home" class="intro">
      <div class="content">
        <div class="row">
          <div class="col-md">
            <span>Fitness and Gym Center</span>
            <div class="content-text">
              <h1>Transforma tu cuerpo en GYM Fitness</h1>
            </div>
            <div class="entry">
              <button class="cta-button">Empieza hoy</button>
            </div>
          </div>
          <div class="col-md">
            <div class="content-image">
              <img
                src="/src/assets/images/intro.png"
                alt="Entrenador Personal"
              />
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Sección de Servicios -->
    <section id="services" class="services">
      <div class="container2">
        <h2>Nuestros Servicios</h2>
        <div class="divider"></div>
        <div class="row">
          <div class="col-md-2">
            <img
              src="/src/assets/images/gallery1.png"
              alt="Entrenador Personal"
            />
            <h3>Entrenadores Personales</h3>
            <p>Entrenadores expertos para alcanzar tus metas.</p>
          </div>
          <div class="col-md-2">
            <img src="/src/assets/images/gallery2.png" alt="Equipos Modernos" />
            <h3>Equipos Modernos</h3>
            <p>Instalaciones equipadas con tecnología de punta.</p>
          </div>
          <div class="col-md-2">
            <img src="/src/assets/images/gallery3.png" alt="Clases Grupales" />
            <h3>Clases Grupales</h3>
            <p>Yoga, spinning, y más para todos los niveles.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Sección de Planes -->
    <section id="planes" class="planes">
      <div class="container3">
        <div class="row"></div>
        <div class="col-md col-md-left">
          <div class="content-left">
            <h2>Nuestros Planes</h2>
            <p>Escoge el plan que más se acomode a tu presupuesto</p>
          </div>
        </div>
        <div class="col-md">
          <div class="content2">
            <h4>Mensual</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing</p>
            <ul>
              <li>
                <i class="la la-check-circle">Instructor</i>
              </li>
              <li>
                <i class="la la-check-circle">Sumplementos</i>
              </li>
              <li>
                <i class="la la-check-circle">Bebidas gratis</i>
              </li>
              <li>
                <i class="la la-check-circle">Soporte Free</i>
              </li>
            </ul>
            <h2>S/70.00</h2>
            <button class="button">Choose Now</button>
          </div>
        </div>
        <div class="col-md">
          <div class="content2">
            <h4>Anual</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing</p>
            <ul>
              <li>
                <i class="la la-check-circle">Instructor</i>
              </li>
              <li>
                <i class="la la-check-circle">Sumplementos</i>
              </li>
              <li>
                <i class="la la-check-circle">Bebidas gratis</i>
              </li>
              <li>
                <i class="la la-check-circle">Soporte Free</i>
              </li>
            </ul>
            <h2>S/150.00</h2>
            <button class="button">Choose Now</button>
          </div>
        </div>
      </div>
    </section>

    <!-- Contáctanos -->
    <div id="contact" class="contact">
      <div class="container4">
        <div class="content-map">
          <iframe
            src="https://www.google.com.pe/maps/place/Grupo+Carley/@-12.0242339,-76.894735,16z
            /data=!4m6!3m5!1s0x9105c3dda21e03f3:0x8b769306d76df33!8m2!3d-12.0261797!4d-
            76.8936802!16s%2Fg%2F11c0vm2hrb?hl=es-419&entry=ttu&g_ep=EgoyMDI0MTIxMS4wIKXMDSoASAFQAw%3D%3D"
            height="510"
            style="border: 0"
            allowfullscreen
            loading="lazy"
          ></iframe>
        </div>
        <div class="row">
          <div class="col-md col-sm-12">
            <h2>Contáctanos</h2>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing, elit.
              Voluptates dignissimos nesciunt repellat minus vero molestiae,
              magnam sed provident similique distinctio.
            </p>
            <div class="row contact-item">
              <div class="col">
                <div class="icon">
                  <i class="fas fa-phone"></i>
                </div>
                <div class="text">
                  <h5>Teléfono</h5>
                  <span>+51 985 758 696</span>
                </div>
              </div>
            </div>
            <div class="row contact-item">
              <div class="col">
                <div class="icon">
                  <i class="fas fa-envelope"></i>
                </div>
                <div class="text">
                  <h5>Email</h5>
                  <span>contacta@dominio.com</span>
                </div>
              </div>
            </div>
            <div class="row contact-item">
              <div class="col">
                <div class="icon">
                  <i class="fas fa-map-marker-alt"></i>
                </div>
                <div class="text">
                  <h5>Local</h5>
                  <span>Av Garcilaso de la Vega 256</span>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md col-sm-12">
            <div class="open">
              <h3>Lunes - Sábado</h3>
              <span>08:00 AM - 12.00 PM</span>
              <h3>Domingos</h3>
              <span>Abierto 24 horas</span>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Testimonios -->
    <section id="testimonials" class="testimonials bg-gray-100 py-16">
      <div class="container mx-auto px-6">
        <!-- Carrusel -->
        <div class="relative overflow-hidden">
          <!-- Carrusel Wrapper -->
          <div
            class="testimonial-wrapper flex transition-transform duration-500 ease-in-out"
            :style="{ transform: `translateX(-${currentIndex * 100}%)` }"
          >
            <!-- Cada slide contiene tres testimonios -->
            <div
              v-for="(group, index) in groupedTestimonials"
              :key="index"
              class="flex flex-shrink-0 w-full"
            >
              <div
                v-for="testimonial in group"
                :key="testimonial.author"
                class="testimonial-slide flex-shrink-0 w-1/3 px-4"
              >
                <div
                  class="bg-white rounded-lg shadow-md p-6 flex flex-col justify-between min-h-[250px] h-[250px]"
                >
                  <p class="text-gray-600 italic mb-4">
                    "{{ testimonial.text }}"
                  </p>
                  <img
                    :src="testimonial.photo"
                    :alt="`Foto de ${testimonial.author}`"
                    class="w-16 h-16 mx-auto rounded-full shadow-lg mb-4"
                  />
                  <h4 class="text-lg font-semibold text-yellow-500">
                    - {{ testimonial.author }}
                  </h4>
                </div>
              </div>
            </div>
          </div>
          <!-- Botones de Navegación -->
          <button
            class="absolute top-1/2 left-0 transform -translate-y-1/2 bg-yellow-500 text-white p-2 rounded-full shadow-md hover:bg-yellow-600 focus:outline-none"
            @click="prevSlide"
          >
            &lt;
          </button>
          <button
            class="absolute top-1/2 right-0 transform -translate-y-1/2 bg-yellow-500 text-white p-2 rounded-full shadow-md hover:bg-yellow-600 focus:outline-none"
            @click="nextSlide"
          >
            &gt;
          </button>
        </div>
      </div>
      <!-- Indicadores -->
      <div class="flex justify-center mt-6">
        <span
          v-for="(group, index) in groupedTestimonials"
          :key="index"
          class="w-3 h-3 mx-1 bg-gray-300 rounded-full cursor-pointer"
          :class="{ 'bg-yellow-500': currentIndex === index }"
          @click="goToSlide(index)"
        >
        </span>
      </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
      <div class="container">
        <p>© 2024 GYM Fitness. Todos los derechos reservados.</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  data() {
    return {
      testimonials: [
        {
          text: "Este gimnasio es increíble, los entrenadores siempre me motivan.",
          photo: "/src/assets/images/testim-2.jpg",
          author: "Juan Pérez",
        },
        {
          text: "¡Las clases grupales me encantan! Siempre me siento bien al terminar una sesión.",
          photo: "/src/assets/images/testim-1.jpg",
          author: "Ana Gómez",
        },
        {
          text: "Un lugar excelente para desconectarme y trabajar en mi salud.",
          photo: "/src/assets/images/testim-3.jpg",
          author: "Pedro Martínez",
        },
        {
          text: "Un gimnasio con una energía positiva increíble. Me siento muy motivado.",
          photo: "/src/assets/images/testim-1.jpg",
          author: "Luisa Herrera",
        },
        {
          text: "¡Excelentes entrenadores! Siempre saben cómo apoyarme.",
          photo: "/src/assets/images/testim-2.jpg",
          author: "Carlos Rivera",
        },
        {
          text: "Las instalaciones son muy modernas y el ambiente es increíble.",
          photo: "/src/assets/images/testim-3.jpg",
          author: "Gabriela López",
        },
      ],
      currentIndex: 0, // Índice actual del carrusel
    };
  },
  computed: {
    groupedTestimonials() {
      // Agrupamos los testimonios en bloques de 3
      return this.testimonials.reduce((acc, testimonial, index) => {
        const groupIndex = Math.floor(index / 3);
        if (!acc[groupIndex]) acc[groupIndex] = [];
        acc[groupIndex].push(testimonial);
        return acc;
      }, []);
    },
  },
  methods: {
    nextSlide() {
      // Mover al siguiente grupo de testimonios
      if (this.currentIndex < this.groupedTestimonials.length - 1) {
        this.currentIndex++;
      } else {
        this.currentIndex = 0; // Volver al inicio
      }
    },
    prevSlide() {
      // Mover al grupo anterior de testimonios
      if (this.currentIndex > 0) {
        this.currentIndex--;
      } else {
        this.currentIndex = this.groupedTestimonials.length - 1; // Ir al último grupo
      }
    },
    goToSlide(index) {
      // Ir a un grupo específico de testimonios
      this.currentIndex = index;
    },
  },
};
</script>
