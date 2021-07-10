<!-- Please remove this file from your project -->
<template>
  <div
    class="relative flex items-top justify-center min-h-screen bg-gray-100 sm:items-center sm:pt-0"
  >
    <link
      href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css"
      rel="stylesheet"
    />
    <div class="max-w-4xl mx-auto sm:px-6 lg:px-8">
      <a
        class="flex justify-center pt-8 sm:pt-0"
        href="https://www.indomascot.com"
        target="_blank"
        alt="Spesialis Pembuatan Kostum Badut Maskot"
      >
        <img src="/loader.png" />
      </a>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: "Spesialis Pembuatan Kostum Badut Maskot",
      description:
        "INDOMASCOT melayani pembuatan kostum badut maskot perusahaan, bisnis, tim olahraga anda sesuai dengan desain dari anda sendiri (custom). (WA 0822-2155-6633)",
      image: "/TIM-PRODUKSI.jpg",
      url: "https://img.indomascot.com",
      name: "INDOMASCOT",
      type: "website",
      site: "@indomascot",
      creator: "@indomascot",
      card: "summary_large_image"
    };
  },
  head() {
    return {
      title: this.title,
      description: this.description,
      meta: [
        // hid is used as unique identifier. Do not use `vmid` for it as it will not work
        {
          hid: "description",
          name: "description",
          content: this.description
        },
        {
          hid: "og:image",
          property: "og:image",
          content: this.image
        },
        {
          hid: "og:site_name",
          name: "og:site_name",
          content: this.name
        },
        {
          hid: "og:type",
          name: "og:type",
          content: this.type
        },
        {
          hid: "og:url",
          name: "og:url",
          content: this.url
        },
        {
          hid: "og:title",
          name: "og:title",
          content: this.title
        },
        {
          hid: "og:description",
          name: "og:description",
          content: this.description
        },
        {
          hid: "twitter:card",
          name: "twitter:card",
          content: this.card
        },
        {
          hid: "twitter:site",
          name: "twitter:site",
          content: this.site
        },
        {
          hid: "twitter:creator",
          name: "twitter:creator",
          content: this.creator
        },
        {
          hid: "twitter:title",
          name: "twitter:title",
          content: this.title
        },
        {
          hid: "twitter:description",
          name: "twitter:description",
          content: this.description
        },
        {
          hid: "twitter:image",
          name: "twitter:image",
          content: this.image
        }
      ]
    };
  }
};
</script>
