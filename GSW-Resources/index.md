<p>This code is in content/_index.md</p>
<!-- 
cd ../..
./themes/blowfish/node_modules/tailwindcss/lib/cli.js -c ./themes/blowfish/tailwind.config.js -i ./themes/blowfish/assets/css/main.css -o ./assets/css/compiled/main.css --jit
-->
booga

{{< list title="Trailheads" cardView=true limit=6 where="Type" value="trailhead" >}}



<div class="container mx-auto px-2">
          <div class="flex flex-wrap">
            <div class="lg:pt-12 pt-6 w-full md:w-4/12 px-4 text-center">
              <div
                class="relative flex flex-col min-w-0 break-words bg-white dark:bg-slate-800 w-full mb-8 shadow-lg rounded-lg border-2 h-60"
              >
                <div class="px-4 py-5 flex-auto">
                  <h5 class="border-b-2 border-neutral-100 px-6 py-3 text-2xl font-medium leading-tight dark:border-black/10">↓ Start Here ↓</h5>
                  <p class="mt-2 mb-4 text-gray-600">
                    <b>Are you new to the Ministik Bird Sanctuary?</b> It's recommended you learn about the area before.
                  </p>
                </div>
                {{< button href="/about" target="_self" >}}
                    Learn More →
                {{< /button >}}
              </div>
            </div>
            <!-- 2nd starts here -->
            <div class="lg:pt-12 pt-6 w-full md:w-4/12 px-4 text-center">
              <div
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg border-2"
              >
                <div class="px-4 py-5 flex-auto">
                  <h6 class="border-b-2 border-neutral-100 px-3 py-3 text-2xl font-medium leading-tight dark:border-white/10">Hikes by Trailhead</h6>
                  <p class="mt-2 mb-4 text-gray-600">
                    Keep you user engaged by providing meaningful information.
                    Remember that by this time, the user is curious.
                  </p>
                </div>
                {{< button href="/trailheads" target="_self" >}}
                    Browse by Trailhead →
                {{< /button >}}
              </div>
            </div>
          <!-- 3rd starts here -->
            <div class="lg:pt-12 pt-6 w-full md:w-4/12 px-4 text-center">
              <div
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg border-2"
              >
                <div class="px-4 py-5 flex-auto">
                  <h6 class="border-b-2 border-neutral-100 px-6 py-3 text-2xl font-medium leading-tight dark:border-white/10">Hikes by Length</h6>
                  <p class="mt-2 mb-4 text-gray-600">
                    Write a few lines about each one. A paragraph describing a
                    feature will be enough. Keep you user engaged!
                  </p>
                </div>
                {{< button href="/about" target="_self" >}}
                    Browse by Hike Length →
                {{< /button >}}
              </div>