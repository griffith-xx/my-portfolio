<script setup>
import IconMysql from "./IconMysql.vue";
import IconBootstrap from "./icons/IconBootstrap.vue";
import IconFlask from "./icons/IconFlask.vue";
import IconFlutter from "./icons/IconFlutter.vue";
import IconLaravel from "./icons/IconLaravel.vue";
import IconMongodb from "./icons/IconMongodb.vue";
import IconNextjs from "./icons/IconNextjs.vue";
import IconPython from "./icons/IconPython.vue";
import IconCloudflare from "./icons/IconCloudflare.vue";
import IconTailwind from "./icons/IconTailwind.vue";
import IconVue from "./icons/IconVue.vue";
import IconGit from "./icons/IconGit.vue";
import IconPostman from "./icons/IconPostman.vue";
import IconJavascript from "./icons/IconJavascript.vue";
import IconTypeScript from "./icons/IconTypeScript.vue";
import IconFigma from "./icons/IconFigma.vue";
</script>

<template>
  <div id="about" class="py-20">
    <h2 class="text-2xl md:text-3xl font-bold tracking-normal mb-1">
      เทคโนโลยีที่ใช้
    </h2>
    <div class="mt-4">
      <h3 class="text-lg font-semibold mb-2">Frontend:</h3>
      <ul
        class="flex flex-wrap gap-9 items-center mt-3 bg-base-200 p-6 rounded-box w-fit w-fit"
      >
        <li>
          <div class="tooltip tooltip-bottom" data-tip="Vue">
            <IconVue />
          </div>
        </li>
        <li>
          <div class="tooltip tooltip-bottom" data-tip="Next js">
            <IconNextjs />
          </div>
        </li>
        <li>
          <div class="tooltip tooltip-bottom" data-tip="JavaScript">
            <IconJavascript />
          </div>
        </li>
        <li>
          <div class="tooltip tooltip-bottom" data-tip="TypeScript">
            <IconTypeScript />
          </div>
        </li>
        <li>
          <div class="tooltip tooltip-bottom" data-tip="Tailwind Css">
            <IconTailwind />
          </div>
        </li>
        <li>
          <div class="tooltip tooltip-bottom" data-tip="Bootstrap 5">
            <IconBootstrap />
          </div>
        </li>
      </ul>
    </div>
    <div class="mt-12">
      <h3 class="text-lg font-semibold mb-2">Backend & API:</h3>
      <ul
        class="flex flex-wrap gap-9 items-center mt-3 bg-base-200 p-6 rounded-box w-fit"
      >
        <li>
          <div class="tooltip tooltip-bottom" data-tip="Laravel">
            <IconLaravel />
          </div>
        </li>
        <li>
          <div class="tooltip tooltip-bottom" data-tip="Python">
            <IconPython />
          </div>
        </li>
      </ul>
    </div>
    <div class="mt-12">
      <h3 class="text-lg font-semibold mb-2">Database:</h3>
      <ul
        class="flex flex-wrap gap-9 items-center mt-3 bg-base-200 p-6 rounded-box w-fit"
      >
        <li>
          <div class="tooltip tooltip-bottom" data-tip="Mysql">
            <IconMysql />
          </div>
        </li>
        <li>
          <div class="tooltip tooltip-bottom" data-tip="Mongodb">
            <IconMongodb />
          </div>
        </li>
      </ul>
    </div>
    <div class="mt-12">
      <h3 class="text-lg font-semibold mb-2">etc:</h3>
      <ul
        class="flex flex-wrap gap-9 items-center mt-3 bg-base-200 p-6 rounded-box w-fit"
      >
        <li>
          <div class="tooltip tooltip-bottom" data-tip="Cloudflare">
            <IconCloudflare />
          </div>
        </li>
        <li>
          <div class="tooltip tooltip-bottom" data-tip="Flask">
            <IconFlask />
          </div>
        </li>
        <li>
          <div class="tooltip tooltip-bottom" data-tip="Flutter">
            <IconFlutter />
          </div>
        </li>
        <li>
          <div class="tooltip tooltip-bottom" data-tip="git">
            <IconGit />
          </div>
        </li>
        <li>
          <div class="tooltip tooltip-bottom" data-tip="Postman">
            <IconPostman />
          </div>
        </li>
        <li>
          <div class="tooltip tooltip-bottom" data-tip="Figma">
            <IconFigma />
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>
