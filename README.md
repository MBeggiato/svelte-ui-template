<p align="center">
 <h1 align="center">
  svelte-ui-template
 </h1>
</p>

Simple skeleton project for sveltekit using:<br>
- [tailwind](https://tailwindcss.com) <img height="15" src="https://user-images.githubusercontent.com/25181517/202896760-337261ed-ee92-4979-84c4-d4b829c7355d.png">
- [skeleton](https://github.com/skeletonlabs/skeleton) <img height="15" src="https://avatars.githubusercontent.com/u/118298875?s=48&v=4">
- [shadcn-svelte](https://github.com/huntabyte/shadcn-svelte) <img height="15" src="https://raw.githubusercontent.com/huntabyte/shadcn-svelte/main/apps/www/static/android-chrome-192x192.png">

## Getting started
<i>I will be using [bun](https://bun.sh) <img height="15" src="https://github.com/marwin1991/profile-technology-icons/assets/136815194/7e9599e9-0570-4bb6-b17f-676ed589912f"> for this project. pnpm, npm etc. should also work.</i>

Clone this project.
```bash
# clone this repo
git clone https://github.com/MBeggiato/svelte-ui-template.git

# install dependencies
bun install
```

## Developing

Once you've installed all modules, run the following to spin up the development:

```bash
bun dev

# or start the server and open the app in a new browser tab
bun dev -- --open
```

## Adding shadcn components
If you want to add components from [shadcn-svelte](https://github.com/huntabyte/shadcn-svelte) you can do so with the following command:

```bash
bunx shadcn-svelte@latest add <component >

# example
bunx shadcn-svelte@latest add accordion
```

For all available components check [this](https://www.shadcn-svelte.com/docs/components/) page.

## Building

To create a production version of your app:

```bash
bun build
```

## Resources
Usefull links: <br>
https://www.shadcn-svelte.com/docs<br>
https://tailwindcss.com/docs/<br>
https://www.skeleton.dev/components/accordions<br>

## License
Licensed under the MIT license.