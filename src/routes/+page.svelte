<script>
  import {
    Heading,
    P,
    A,
    Mark,
    Secondary,
    Button,
    DarkMode,
  } from "flowbite-svelte";
</script>

<section class="landing-section">
  <div class="text-center">
    <DarkMode />
    <Heading
      tag="h1"
      class="mb-4"
      customSize="text-4xl font-extrabold  md:text-5xl lg:text-6xl"
      >Create proposals & invoices instantly!</Heading
    >
    <P
      class="mb-6 text-lg lg:text-xl sm:px-16 xl:px-48 dark:text-gray-400 text-center text-white-60"
      >Simplify proposal and invoice creation with our user-friendly,
      time-saving tool</P
    >
    <Button href="/proposal/client-info"
      >Create Proposal
      <svg
        class="ml-2 -mr-1 w-5 h-5"
        fill="currentColor"
        viewBox="0 0 20 20"
        xmlns="http://www.w3.org/2000/svg"
        ><path
          fill-rule="evenodd"
          d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
          clip-rule="evenodd"
        /></svg
      >
    </Button>
  </div>
</section>
