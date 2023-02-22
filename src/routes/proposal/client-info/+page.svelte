<script>
  import {
    Heading,
    P,
    A,
    Mark,
    Secondary,
    Button,
    DarkMode,
    Label,
    Input,
    Textarea,
    Progressbar,
  } from "flowbite-svelte";
  let textareaprops = {
    id: "message",
    name: "message",
    label: "Your message",
    rows: 4,
    placeholder: "Leave a comment...",
  };
</script>

<div class="text-center pb-5">
  <DarkMode />
  <Heading tag="h2" customSize="text-4xl font-extrabold"
    >Create a Proposal</Heading
  >
  <P
    class="mb-6 text-lg lg:text-xl sm:px-16 xl:px-48 dark:text-gray-400 text-center text-white-60 mt-3"
    >Fill in the data below, and it’ll preview</P
  >
</div>

<div class="flex justify-center">
  <div class="p-8 rounded-lg  w-[570px]">
    <Heading tag="h4" class="mb-6">Client Info</Heading>

    <div class="mb-6">
      <Label for="default-input" class="block mb-2">Client Name</Label>
      <Input id="default-input" placeholder="John Doe" />
    </div>

    <div class="mb-6">
      <Label for="default-input" class="block mb-2">Company Name</Label>
      <Input id="default-input" placeholder="Apple.inc" />
    </div>

    <div class="mb-6">
      <Label for="default-input" class="block mb-2">Client Email</Label>
      <Input id="email" type="email" placeholder="Johndoe@gmail.com" />
    </div>

    <div class="mb-6">
      <Label for="textarea-id" class="block mb-2">Company Overview</Label>
      <Textarea
        id="textarea-id"
        class="mb-2"
        placeholder="Apple Inc. is a multinational technology company based in Cupertino, California. It is known for designing, developing, and selling consumer electronics, computer software, and online services.        "
      />
    </div>
  </div>
  <Button href="/proposal/project-info"
    >Next
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

  <div class="my-4">
    <div class="mb-1 text-base font-medium dark:text-white w-[100px]" />
    <Progressbar progress="25" size="h-1.5" />
  </div>
</div>
