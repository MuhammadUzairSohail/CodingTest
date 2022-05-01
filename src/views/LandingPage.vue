<template>
  <!--  Header-->
  <header class="grid grid-cols-12 justify-between px-4 py-4 border-b">
    <div class="flex items-center gap-6 border-r col-span-1">
      <img src="https://cress.gigsalad.com/images/logo.svg" class="h-14 w-14">
      <div class="flex items-center">
        Menu
        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 ml-2" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
          <path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7" />
        </svg>
      </div>
    </div>
    <div class="flex items-center gap-4 px-4 col-span-9">
      <div>
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 stroke-gray-400" fill="none" viewBox="0 0 24 24" stroke-width="2">
          <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
        </svg>
      </div>
      <input type="text" class="w-full border-0 border-gray-400 p-2 focus:outline-0 focus:ring-0" placeholder="What kind of talent or service can we help you find?">
    </div>

    <div class="border-l flex items-center gap-4 px-4 col-span-2">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 stroke-gray-400" fill="none" viewBox="0 0 24 24" stroke-width="2">
        <path stroke-linecap="round" stroke-linejoin="round" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
      </svg>
      <div class="ml-4">
        Log In
      </div>
      <div class="bg-blue-400 px-4 py-2 text-white rounded ml-4">
        List your service
      </div>
    </div>
  </header>
  <!--  Body-->

  <div class="flex items-center justify-evenly py-6 relative">
    <div class="">
      <img src="https://cress.gigsalad.com/images/portraits/princess--421w.jpg" style="width: 421px; height: 675px;">
    </div>
    <div class="py-4 px-4">
      <h1 class="text-5xl font-bold text-gray-700 leading-snug">
        <span class="text-[#2690ff]">Book something <br> awesome ®</span> for your <br>next event
      </h1>
      <small>From birthday parties to weddings, we’ll help you book the best talent for any occasion.</small>
    </div>
    <div class="flex items-center gap-4 p-4 rounded w-3/5 absolute bg-[#eef1f5]" style="bottom: 15%;">
      <div>
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 stroke-gray-400" fill="none" viewBox="0 0 24 24" stroke-width="2">
          <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
        </svg>
      </div>
      <input type="text" class="w-full border-0 bg-[#eef1f5] border-gray-300 p-2 focus:outline-0 bg-gray-300 focus:ring-0" placeholder="What kind of talent or service can we help you find?">
      <div class="bg-blue-500 px-12 py-3 font-bold text-white rounded">
        Search
      </div>
    </div>
  </div>

  <div class="bg-gray-100 py-12">
    <div class="text-center text-3xl font-bold text-gray-800">
      Whatever you’re planning,<br>
      make it extraordinary.
    </div>
    <div>
      <div class="text-center mt-8 text-2xl font-semibold text-gray-800">
        Musical Acts
      </div>
      <div class="flex justify-center items-center gap-4 mt-6">
        <div class="h-64 w-64 text-center grid grid-rows-2 items-end py-6 rounded" style="background-image: url(https://cress.gigsalad.com/images/home-slider-categories/BandsGroups.jpg);">
          <div></div>
          <div>
            <h4 class="text-white text-xl font-bold">Bands &amp; Groups</h4>
            <p class="text-white font-semibold">Blues Bands, Mariachis,<br> Wedding Bands…</p>
          </div>
        </div>
        <div class="h-64 w-64 text-center grid grid-rows-2 items-end py-6 rounded" style="background-image: url(https://cress.gigsalad.com/images/home-slider-categories/BandsGroups.jpg);">
          <div></div>
          <div>
            <h4 class="text-white text-xl font-bold">Bands &amp; Groups</h4>
            <p class="text-white font-semibold">Blues Bands, Mariachis,<br> Wedding Bands…</p>
          </div>
        </div>
        <div class="h-64 w-64 text-center grid grid-rows-2 items-end py-6 rounded" style="background-image: url(https://cress.gigsalad.com/images/home-slider-categories/BandsGroups.jpg);">
          <div></div>
          <div>
            <h4 class="text-white text-xl font-bold">Bands &amp; Groups</h4>
            <p class="text-white font-semibold">Blues Bands, Mariachis,<br> Wedding Bands…</p>
          </div>
        </div>
        <div class="h-64 w-64 text-center grid grid-rows-2 items-end py-6 rounded" style="background-image: url(https://cress.gigsalad.com/images/home-slider-categories/BandsGroups.jpg);">
          <div></div>
          <div>
            <h4 class="text-white text-xl font-bold">Bands &amp; Groups</h4>
            <p class="text-white font-semibold">Blues Bands, Mariachis,<br> Wedding Bands…</p>
          </div>
        </div>
      </div>
    </div>
    <div class="mt-4">
      <div class="text-center mt-8 text-2xl font-semibold text-gray-800">
        Entertainers
      </div>
      <div class="flex justify-center items-center gap-4 mt-6">
        <div class="h-64 w-64 text-center grid grid-rows-2 items-end py-6 rounded" style="background-image: url(https://cress.gigsalad.com/images/home-slider-categories/CircusAcrobatic.jpg);">
          <div></div>
          <div>
            <h4 class="text-white text-xl font-bold">Bands &amp; Groups</h4>
            <p class="text-white font-semibold">Blues Bands, Mariachis,<br> Wedding Bands…</p>
          </div>
        </div>
        <div class="h-64 w-64 text-center grid grid-rows-2 items-end py-6 rounded" style="background-image: url(https://cress.gigsalad.com/images/home-slider-categories/CircusAcrobatic.jpg);">
          <div></div>
          <div>
            <h4 class="text-white text-xl font-bold">Bands &amp; Groups</h4>
            <p class="text-white font-semibold">Blues Bands, Mariachis,<br> Wedding Bands…</p>
          </div>
        </div>
        <div class="h-64 w-64 text-center grid grid-rows-2 items-end py-6 rounded" style="background-image: url(https://cress.gigsalad.com/images/home-slider-categories/CircusAcrobatic.jpg);">
          <div></div>
          <div>
            <h4 class="text-white text-xl font-bold">Bands &amp; Groups</h4>
            <p class="text-white font-semibold">Blues Bands, Mariachis,<br> Wedding Bands…</p>
          </div>
        </div>
        <div class="h-64 w-64 text-center grid grid-rows-2 items-end py-6 rounded" style="background-image: url(https://cress.gigsalad.com/images/home-slider-categories/CircusAcrobatic.jpg);">
          <div></div>
          <div>
            <h4 class="text-white text-xl font-bold">Bands &amp; Groups</h4>
            <p class="text-white font-semibold">Blues Bands, Mariachis,<br> Wedding Bands…</p>
          </div>
        </div>
      </div>
    </div>
    <div class="mt-4">
      <div class="text-center mt-8 text-2xl font-semibold text-gray-800">
        Event Services
      </div>
      <div class="flex justify-center items-center gap-4 mt-6">
        <div class="h-64 w-64 text-center grid grid-rows-2 items-end py-6 rounded" style="background-image: url(https://cress.gigsalad.com/images/home-slider-categories/BandsGroups.jpg);">
          <div></div>
          <div>
            <h4 class="text-white text-xl font-bold">Bands &amp; Groups</h4>
            <p class="text-white font-semibold">Blues Bands, Mariachis,<br> Wedding Bands…</p>
          </div>
        </div>
        <div class="h-64 w-64 text-center grid grid-rows-2 items-end py-6 rounded" style="background-image: url(https://cress.gigsalad.com/images/home-slider-categories/BandsGroups.jpg);">
          <div></div>
          <div>
            <h4 class="text-white text-xl font-bold">Bands &amp; Groups</h4>
            <p class="text-white font-semibold">Blues Bands, Mariachis,<br> Wedding Bands…</p>
          </div>
        </div>
        <div class="h-64 w-64 text-center grid grid-rows-2 items-end py-6 rounded" style="background-image: url(https://cress.gigsalad.com/images/home-slider-categories/BandsGroups.jpg);">
          <div></div>
          <div>
            <h4 class="text-white text-xl font-bold">Bands &amp; Groups</h4>
            <p class="text-white font-semibold">Blues Bands, Mariachis,<br> Wedding Bands…</p>
          </div>
        </div>
        <div class="h-64 w-64 text-center grid grid-rows-2 items-end py-6 rounded" style="background-image: url(https://cress.gigsalad.com/images/home-slider-categories/BandsGroups.jpg);">
          <div></div>
          <div>
            <h4 class="text-white text-xl font-bold">Bands &amp; Groups</h4>
            <p class="text-white font-semibold">Blues Bands, Mariachis,<br> Wedding Bands…</p>
          </div>
        </div>
      </div>
    </div>
    <div class="text-center text-lg mt-6 font-bold text-gray-700">
      or
    </div>
    <div class="text-center text-lg mt-4 font-bold underline text-gray-700">
      Browse Event-Specific Vendors
    </div>
  </div>
  <div>
    <div class="text-center text-3xl font-semibold text-gray-700">
      Over 110,000 bands, entertainers,<br> and event services for hire.
    </div>
    <div class="flex justify-center items-center p-12">
      <div class="space-y-8">
        <div class="flex items-center gap-8">
          <img src="https://cress.gigsalad.com/images/svg/standalone/how-it-works/browse-compare.svg" width="79" height="47">
          <div>
            <h1 class="text-xl font-semibold">Browse and compare.</h1>
            <p>Compare rates and availability of local <br> entertainers and vendors.</p>
          </div>
        </div>
        <div class="flex items-center gap-8">
          <img src="https://cress.gigsalad.com/images/svg/standalone/how-it-works/browse-compare.svg" width="79" height="47">
          <div>
            <h1 class="text-xl font-semibold">Browse and compare.</h1>
            <p>Compare rates and availability of local <br> entertainers and vendors.</p>
          </div>
        </div>
        <div class="flex items-center gap-8">
          <img src="https://cress.gigsalad.com/images/svg/standalone/how-it-works/browse-compare.svg" width="79" height="47">
          <div>
            <h1 class="text-xl font-semibold">Browse and compare.</h1>
            <p>Compare rates and availability of local <br> entertainers and vendors.</p>
          </div>
        </div>
      </div>
      <div>
        <img src="https://cress.gigsalad.com/images/how-it-works-laptop--755w.jpg" width="755" height="528">
      </div>
    </div>
    <div class="text-center">
      <button class="bg-blue-500 px-12 py-3 font-bold text-white rounded mb-4">
        Get Started
      </button><br>
      <span class="text-blue-500"> Book something awesome.®</span>
    </div>
    <div class="mt-36">
      <img src="https://cress.gigsalad.com/images/performer-scroll-profiles.png" style="transform: scale(1.5)">
    </div>
    <div class="flex flex-col items-center bg-gray-100 p-36">
      <div class="font-bold text-gray-800 text-3xl">
        Joining GigSalad is quick and easy.
      </div>
      <div class="flex justify-center items-center gap-4 mt-8">
        <div class="flex justify-center items-center gap-8 h-86 w-[500px] bg-white px-12 pt-12 pb-6 rounded cursor-pointer text-gray-700 hover:-translate-y-4 hover:text-blue-500 hover:shadow-lg transition-all duration-700">
          <div>
            <svg width="24" height="48" viewBox="0 0 24 48" xmlns="http://www.w3.org/2000/svg" class="home__join-section-icon mt-6">
              <title>
                Lightning
              </title>
              <g fill="none" fill-rule="evenodd">
                <path d="M21.1314829 18H13c-.7854355 0-1.2642783-.8639509-.8479983-1.5299989L21.1957524 2H7.7807764l-5.5 22H9c.65937342 0 1.1382564.6269778.96476382 1.2631174l-4.3785975 16.0548575L21.1314829 18z" fill="#E1E5E9" class="lightning-fill"></path>
                <path d="M21.1314829 18H13c-.7854355 0-1.2642783-.8639509-.8479983-1.5299989L21.1957524 2H7.7807764l-5.5 22H9c.65937342 0 1.1382564.6269778.96476382 1.2631174l-4.3785975 16.0548575L21.1314829 18zM23 16c.7986954 0 1.2750868.8901455.8320503 1.5547002l-20 30c-.62925472.9438821-2.09529584.2766154-1.79681412-.8178176L7.6907496 26H1c-.65057115 0-1.12792918-.6113889-.9701425-1.2425356l6-24.00000002C6.14114925.31229738 6.54113236 0 7 0h16c.7854355 0 1.2642783.86395093.8479983 1.52999894L14.8042476 16H23z" fill-rule="nonzero" fill="#47525D" class="lightning-outline"></path>
              </g>
            </svg>
            <h3 class="text-2xl mt-2 font-bold ">
              For Gigging Professionals
            </h3>
            <h4 class="text-md mt-4 font-semibold text-gray-700">
              Are you a performer, speaker, or event services provider?
            </h4>
            <p class="mt-4 text-sm text-gray-700">GigSalad provides a full-service platform for booking gigs. Get leads, send quotes, and collect payments all in one place.</p>
          </div>
          <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 stroke-gray-300" fill="none" viewBox="0 0 24 24" stroke-width="2">
            <path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7" />
          </svg>
        </div>
        <div class="flex justify-center items-center gap-8 h-86 w-[500px] bg-white px-12 pt-12 pb-6 rounded cursor-pointer text-gray-700 hover:-translate-y-4 hover:text-blue-500 hover:shadow-lg transition-all duration-700">
          <div>
            <svg width="32" height="48" viewBox="0 0 32 48" xmlns="http://www.w3.org/2000/svg" class="home__join-section-icon mt-6">
              <title>
                Clipboard
              </title>
              <g fill="none" fill-rule="evenodd">
                <path d="M21.0557581 4.38095238h5.4893547c.5522847 0 1 .44771525 1 1v4.38095238c0 .55228474-.4477153 1.00000004-1 1.00000004H5.21679198c-.55228475 	0-1-.4477153-1-1.00000004V5.38095238c0-.55228475.44771525-1 1-1h5.48944062C11.1648342 1.89157448 13.303573 0 15.8809524 0c2.5787489 0 4.7165246 1.89113422 5.1748057 4.38095238zm4.4893547 2h-5.3984963c-.5522847 0-1-.44771525-1-1C19.1466165 3.50823948 17.6785747 2 15.8809524 2c-1.7963055 0-3.2656642 1.50907108-3.2656642 3.38095238 0 .55228475-.4477152 1-1 1H6.21679198v2.38095238H25.5451128V6.38095238z" fill="#3D464D" class="clipboard-outline" fill-rule="nonzero"></path>
                <path fill="#DDE1E6" class="clipboard-fill" d="M29.8107769 10.7619048H1.95112782V46H29.8107769"></path>
                <path d="M29.8107769 10.7619048H1.95112782V46H29.8107769V10.7619048zm2-1.00000004V47c0 .5522847-.4477152 1-1 1H.95112782c-.55228475 0-1-.4477153-1-1V9.76190476c0-.55228475.44771525-1 	1-1H30.8107769c.5522848 0 1 .44771525 1 1z" fill="#3D464D" class="clipboard-outline" fill-rule="nonzero"></path>
                <path d="M11.6152882 18.4285714h12.7969925c.5522848 0 1-.4477152 1-1 0-.5522847-.4477152-1-1-1H11.6152882c-.5522847 0-1 .4477153-1 1 0 .5522848.4477153 1 1 1zm0 6.5714286h12.7969925c.5522848 0 	1-.4477153 1-1s-.4477152-1-1-1H11.6152882c-.5522847 0-1 .4477153-1 1s.4477153 1 1 1zm0 6.5714286h12.7969925c.5522848 0 1-.4477153 1-1 0-.5522848-.4477152-1-1-1H11.6152882c-.5522847 0-1 .4477152-1 1 0 .5522847.4477153 1 1 1zm0 6.5714285h12.7969925c.5522848 0 1-.4477152 1-1 0-.5522847-.4477152-1-1-1H11.6152882c-.5522847 0-1 .4477153-1 1 0 .5522848.4477153 1 1 1zM6.28320802 18.4285714h1.06641604c.55228475 0 1-.4477152 1-1 0-.5522847-.44771525-1-1-1H6.28320802c-.55228475 0-1 .4477153-1 1 0 .5522848.44771525 1 1 1zm0 6.5714286h1.06641604c.55228475 0 1-.4477153 1-1s-.44771525-1-1-1H6.28320802c-.55228475 0-1 .4477153-1 1s.44771525 1 1 1zm0 6.5714286h1.06641604c.55228475 0 1-.4477153 1-1 0-.5522848-.44771525-1-1-1H6.28320802c-.55228475 0-1 .4477152-1 1 0 .5522847.44771525 1 1 1zm0 6.5714285h1.06641604c.55228475 0 1-.4477152 1-1 0-.5522847-.44771525-1-1-1H6.28320802c-.55228475 0-1 .4477153-1 1 0 .5522848.44771525 1 1 1z" fill="#3D464D" class="clipboard-outline" fill-rule="nonzero"></path>
              </g>
            </svg>
            <h3 class="text-2xl mt-2 font-bold ">
              For Gigging Professionals
            </h3>
            <h4 class="text-md mt-4 font-semibold text-gray-700">
              Are you a performer, speaker, or event services provider?
            </h4>
            <p class="mt-4 text-sm text-gray-700">GigSalad provides a full-service platform for booking gigs. Get leads, send quotes, and collect payments all in one place.</p>
          </div>
          <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 stroke-gray-300" fill="none" viewBox="0 0 24 24" stroke-width="2">
            <path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7" />
          </svg>
        </div>
      </div>
    </div>
  </div>

  <div class="flex flex-col items-center py-8">
    <div class="font-bold text-gray-800 text-3xl text-center">
      Millions trust GigSalad to electrify <br> their events.
    </div>
    <div class="flex justify-center items-center gap-44 mt-16">
      <img src="https://cress.gigsalad.com/images/testimonials/logo--americas-got-talent--106w.png">
      <img src="https://cress.gigsalad.com/images/testimonials/logo--mcdonalds--52w.png">
      <img src="https://cress.gigsalad.com/images/testimonials/logo--americas-got-talent--106w.png">
      <img src="https://cress.gigsalad.com/images/testimonials/logo--mcdonalds--52w.png">
    </div>
    <div class="flex justify-center items-center gap-44 mt-16">
      <img src="https://cress.gigsalad.com/images/testimonials/logo--americas-got-talent--106w.png">
      <img src="https://cress.gigsalad.com/images/testimonials/logo--mcdonalds--52w.png">
      <img src="https://cress.gigsalad.com/images/testimonials/logo--americas-got-talent--106w.png">
      <img src="https://cress.gigsalad.com/images/testimonials/logo--mcdonalds--52w.png">
    </div>
  </div>

  <div class="bg-gray-800 p-16">
    <div class="text-white grid grid-cols-6 mb-12 gap-16 container mx-auto px-16">
      <img src="https://cress.gigsalad.com/images/logo.svg" width="60" height="60" class="push--bottom--small" alt="GigSalad – Entertainment Marketplace">
      <div>
        <h1 class="font-semibold">Company</h1>
        <div class="mt-2">
          <a href="#" class="">About us</a>
        </div>
        <div class="mt-2">
          <a href="#" class="">About us</a>
        </div>
        <div class="mt-2">
          <a href="#" class="">About us</a>
        </div>
      </div>
      <div>
        <h1 class="font-semibold">Event Planners</h1>
        <div class="mt-2">
          <a href="#" class="">About us</a>
        </div>
        <div class="mt-2">
          <a href="#" class="">About us</a>
        </div>
        <div class="mt-2">
          <a href="#" class="">About us</a>
        </div>
      </div>
      <div>
        <h1 class="font-semibold">Vendors</h1>
        <div class="mt-2">
          <a href="#" class="">About us</a>
        </div>
        <div class="mt-2">
          <a href="#" class="">About us</a>
        </div>
        <div class="mt-2">
          <a href="#" class="">About us</a>
        </div>
      </div>
      <div>
        <h1 class="font-semibold">Support</h1>
        <div class="mt-2">
          <a href="#" class="">About us</a>
        </div>
        <div class="mt-2">
          <a href="#" class="">About us</a>
        </div>
        <div class="mt-2">
          <a href="#" class="">About us</a>
        </div>
      </div>
      <div>

      </div>
    </div>
    <div class="text-white flex justify-between container mx-auto text-sm px-16">
      <p class="">© GigSalad 2022 <span class="text-blue-500">❤ Peace, Love &amp; Gigs ®</span></p>
      <div class="grid grid-cols-2 gap-16">
        <a href="#" class="">Privacy</a>
        <a href="#" class="">Terms</a>
      </div>

    </div>
  </div>

</template>

<script>
export default {
  name: 'LandingPage',
}
</script>

<style scoped>

</style>
