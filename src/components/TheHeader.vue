<template>
    <header
        role="banner"
        class="3xl:tw-container tw-fixed tw-inset-x-2 tw-top-1 tw-z-50 tw-mx-auto sm:tw-top-2"
    >
      <div class="tw-flex tw-justify-between md:tw-p-1 lg:tw-py-2 2xl:tw-px-0">
        <div class="tw-px-3 tw-py-2 tw-font-medium sm:tw-hidden">
          <a
              class="tw-bg-gradient-to-r tw-from-purple tw-to-blue tw-bg-clip-text tw-font-display tw-font-bold tw-text-transparent"
              title="scroll to top"
              href="#"
          >
            L.
          </a>
        </div>
        <div class="md:tw-visible">
          <a
              class="tw-hidden tw-rounded-lg tw-px-3 tw-py-2 tw-text-base tw-font-semibold hover:tw-bg-slate-200 hover:tw-text-blue sm:tw-block md:tw-text-2xl"
              title="scroll to top"
              href="#"
          >
            Home
          </a>
        </div>

        <nav class="tw-flex tw-justify-center tw-px-3 tw-text-base tw-font-semibold sm:tw-space-x-4 md:tw-text-2xl">
          <a
              href="#about"
              class="tw-rounded-lg tw-px-3 tw-py-2 hover:tw-bg-slate-200 hover:tw-text-blue"
          >
            About
          </a>
          <a
              href="#expertise"
              class="tw-rounded-lg tw-px-3 tw-py-2 hover:tw-bg-slate-200 hover:tw-text-blue"
          >
            Expertise
          </a>
          <a
              href="#contact"
              class="tw-rounded-lg tw-px-3 tw-py-2 hover:tw-bg-slate-200 hover:tw-text-blue"
          >
            Contact
          </a>
        </nav>
      </div>
    </header>
</template>
