<template>
    <section class="tw-mx-auto">
      <div class="tw-mx-auto tw-mt-10 md:tw-mt-80 md:tw-w-2/3 md:tw-p-8">
        <blockquote class="tw-mb-4 tw-border-8 tw-border-lime-400 tw-p-10 tw-text-base tw-font-bold sm:tw-text-xl md:tw-pl-20 md:tw-text-5xl">
          <!-- "Somewhere between design – a world of personas, pixels, and polish – and engineering – a world of logic, loops, and Linux – lies frontend design."  -->
          <!-- "The next generation of fintech companies may look like a bank without actually being a bank."  -->
          "It’s not that we need new ideas, but we need to stop having old ideas."
          <cite class="tw-mt-10 tw-block tw-text-base tw-font-semibold tw-not-italic">
            Edwin Land 
            <a
                href="https://ripple.com/"
                class="tw-text-blue hover:tw-text-purple-600"
                target="_blank"
            ></a>
          </cite>
        </blockquote>
      </div>
      <div class="md:tw-flex md:tw-justify-end">
        <div class="tw-my-20 tw-px-10 tw-text-base md:tw-w-3/5 md:tw-pr-48 md:tw-text-xl">
          <p class="tw-mb-10">
            <!-- I am, in short, a designer, who eventually discovered the joy of coding and somehow ended up sitting full-time on the engineer's and 
            back-end developer's floor. It took me a while, to be honest, but I have successfully recovered from my identity crisis
            and found myself the right spot:<wbr> A place where I can bridge the often scary gap 
            between the design and development worlds, 
            spreading peace, harmony, and naming conventions. -->
            <!-- MorganFinway stands as a beacon of innovation in the ever-evolving landscape of financial technology. Founded with a vision to redefine the boundaries of possibility in the fintech sector, we have emerged as a dynamic force committed to revolutionizing the way finance operates. Our journey is steeped in a dedication to pushing the boundaries of conventional thinking and consistently delivering cutting-edge software solutions. At the core of MorganFinway is a passionate team of experts, driven by the belief that technology can empower businesses and individuals to achieve unparalleled success. -->
            At MorganSurge, we are passionate about nurturing the potential within your organization. Our mission is to empower employees with the knowledge, skills, and opportunities they need to not only excel in their current roles but also to thrive in the ever-evolving landscape of the modern workplace.
      We believe that when employees are empowered to reach their full potential, your organization will reap the rewards of increased productivity, employee satisfaction, and long-term success.
          </p>
          <p>
            MorganSurge is a trailblazing force in the tech realm, dedicated to transforming the way how softwareware works. With a focus on innovation, empowerment, and reliability, we bring a fresh perspective to software solutions tailored for innovation.
            <!-- That said, I'm not a traditional graphic designer, 
            but I have a strong knowledge of the design aspects of modern web development. 
            I understand UX principles and I know how to apply them. <wbr>
            I'm not a full-stack developer, but I am happy to write clean front-end code and
            create user interfaces that are responsive, performant, flexible, and compatible.  -->
          </p>
        </div>
      </div>
      <next-section-link
          container-class="md:tw-mt-20"
          target="#experience"
          title=""
      />
    </section>
</template>


<script lang="ts">
import { defineComponent } from 'vue'
import NextSectionLink from './NextSectionLink.vue'

export default defineComponent({
    components: { 
      NextSectionLink,
     },
    props: {
    },
})
</script>