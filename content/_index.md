---
title: "All that Jazz"
description: "This is a demo of adding content to the homepage."
---

{{< 
    video src="StompyReel" 
    preload="true"
    width="100%"
    muted="true"
    autoplay="true"
    loop="true" 
    controls="false"
    preload="true"
>}}

<div class="flex px-4 py-2 mb-8 text-base rounded-md bg-primary-100 dark:bg-primary-900">
  <span class="flex items-center ltr:pr-3 rtl:pl-3 text-primary-400">
    {{< icon "triangle-exclamation" >}}
  </span>
  <span class="flex items-center justify-between grow dark:text-neutral-300">
    <span class="prose dark:prose-invert">Hey, if you like what you see, contact me!</span>
    <a href = "mailto:massimiliano.truzzi@gmail.com">
        <button
        class="px-4 !text-neutral !no-underline rounded-md bg-primary-600 hover:!bg-primary-500 dark:bg-primary-800 dark:hover:!bg-primary-700"
        >
        contact me
        </button>
    </a>
  </span>
</div>