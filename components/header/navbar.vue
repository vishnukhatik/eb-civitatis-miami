<template>
  <div id="nav-bar">
    <div class="flex">
      <nav class="w-full eb-nav-container">
        <ul
          class="eb-nav-menu w-full sm:w-auto self-end sm:self-center sm:flex flex-col sm:flex-row items-center h-full sm:py-0 sm:pb-0 hidden"
        >
          <li
            class="eb-nav-menu-list text-white text-lg w-full no-underline sm:w-auto sm:p-4"
          >
            <nuxt-link to="" class="sm:p-4 menu-link">Travel Guide</nuxt-link>
            <div class="eb-nav-megamenu">
              <v-container>
                <v-row>
                  <v-col cols="12" sm="3" md="3" class="eb-brd-t eb-brd-b">
                    <a
                      href="/general-information"
                      class="eb-nav-megamenu-child-title"
                      title="General Information"
                    >
                      <span class="flex items-center">
                        <feather type="info"></feather> &nbsp;General
                        Information</span
                      >
                    </a>
                    <ul>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link">
                            Plan your trip</span
                          >
                        </a>
                        <a href="#" class="o-arrow-open"></a>
                      </li>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link">
                            Neighbourhoods</span
                          >
                        </a>
                        <a href="#" class="o-arrow-open"></a>
                      </li>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link">
                            History</span
                          >
                        </a>
                      </li>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link"> Photos</span>
                        </a>
                      </li>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link">
                            Show all</span
                          >
                        </a>
                      </li>
                    </ul>
                  </v-col>
                  <v-col cols="12" sm="3" md="3" class="eb-brd-t eb-brd-b">
                    <a
                      href="/general-information"
                      class="eb-nav-megamenu-child-title"
                      title="General Information"
                    >
                      <span class="flex items-center">
                        <feather type="heart"></feather> &nbsp;Attractions</span
                      >
                    </a>
                    <ul>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link"> Top 10</span>
                        </a>
                        <a href="#" class="o-arrow-open"></a>
                      </li>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link">
                            Tourist attractions</span
                          >
                        </a>
                        <a href="#" class="o-arrow-open"></a>
                      </li>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link">
                            Museums and Galleries</span
                          >
                        </a>
                        <a href="#" class="o-arrow-open"></a>
                      </li>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link">
                            Beaches</span
                          >
                        </a>
                        <a href="#" class="o-arrow-open"></a>
                      </li>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link">
                            Day Trips</span
                          >
                        </a>
                        <a href="#" class="o-arrow-open"></a>
                      </li>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link">
                            Show All</span
                          >
                        </a>
                      </li>
                    </ul>
                  </v-col>
                  <v-col cols="12" sm="3" md="3" class="eb-brd-t eb-brd-b">
                    <a
                      href="/general-information"
                      class="eb-nav-megamenu-child-title"
                      title="General Information"
                    >
                      <span class="flex items-center">
                        <i class="ti-direction eb-menu-icon"></i> &nbsp;Getting
                        there</span
                      >
                    </a>
                    <ul>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link"
                            >Miami Airport</span
                          >
                        </a>
                      </li>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link">
                            Show all</span
                          >
                        </a>
                      </li>
                    </ul>
                  </v-col>
                  <v-col cols="12" sm="3" md="3" class="eb-brd-b">
                    <a
                      href="/general-information"
                      class="eb-nav-megamenu-child-title"
                      title="General Information"
                    >
                      <span class="flex items-center">
                        <i class="ti-truck eb-menu-icon"></i>
                        &nbsp;Transport</span
                      >
                    </a>
                    <ul>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link">
                            Car Rental</span
                          >
                        </a>
                      </li>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link">
                            Metromover</span
                          >
                        </a>
                      </li>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link">
                            Metrorail</span
                          >
                        </a>
                      </li>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link">
                            Metrobus</span
                          >
                        </a>
                      </li>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link">
                            Show all</span
                          >
                        </a>
                      </li>
                    </ul>
                  </v-col>
                  <v-col cols="12" sm="3" md="3" class="eb-brd-t">
                    <a
                      href="/general-information"
                      class="eb-nav-megamenu-child-title"
                      title="General Information"
                    >
                      <span class="flex items-center">
                        <i class="ti-wallet eb-menu-icon"></i> &nbsp;Saving
                        Money</span
                      >
                    </a>
                    <ul>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link">
                            Go Miami Card</span
                          >
                        </a>
                      </li>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link"
                            >Miami & The Keys Explorer Pass</span
                          >
                        </a>
                      </li>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link">
                            Show all</span
                          >
                        </a>
                      </li>
                    </ul>
                  </v-col>
                  <v-col cols="12" sm="3" md="3" class="eb-brd-t">
                    <a
                      href="/general-information"
                      class="eb-nav-megamenu-child-title"
                      title="General Information"
                    >
                      <span class="flex items-center">
                        <feather type="shopping-bag"></feather>
                        &nbsp;Shopping</span
                      >
                    </a>
                    <ul>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link">
                            Dolphin Mall</span
                          >
                        </a>
                      </li>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link"
                            >Aventura Mall</span
                          >
                        </a>
                      </li>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link"
                            >Sawgrass Mills Mall</span
                          >
                        </a>
                      </li>
                      <li class="flex justify-between">
                        <a href="/plan-your-trip" title="Plan your trip">
                          <span class="eb-nav-third-element-link">
                            Show all</span
                          >
                        </a>
                      </li>
                    </ul>
                  </v-col>
                  <v-col cols="12" sm="3" md="3" class="eb-brd-t">
                    <a
                      href="/general-information"
                      class="eb-nav-megamenu-child-title"
                      title="General Information"
                    >
                      <span class="flex items-center">
                        <i class="ti-hand-drag eb-menu-icon"></i> &nbsp;Where to
                        eat</span
                      >
                    </a>
                    <a
                      href="/general-information"
                      class="eb-nav-megamenu-child-title"
                      title="General Information"
                    >
                      <span class="flex items-center">
                        <i class="ti-home eb-menu-icon"></i> &nbsp;Where to
                        stay</span
                      >
                    </a>
                  </v-col>
                  <v-col cols="12" sm="3" md="3" class="">
                    <a
                      href="/general-information"
                      class="eb-nav-megamenu-child-title"
                      title="General Information"
                    >
                      <span class="flex items-center">
                        <feather type="map"></feather>
                        &nbsp;Map</span
                      >
                    </a>
                  </v-col>
                </v-row>
              </v-container>
            </div>
          </li>
          <li
            class="eb-nav-menu-list text-white text-lg w-full no-underline sm:w-auto sm:p-4"
          >
            <nuxt-link to="" class="sm:p-4 menu-link"
              >Day trips and guided tours</nuxt-link
            >
          </li>
          <li
            class="eb-nav-menu-list text-white text-lg w-full no-underline sm:w-auto sm:p-4"
          >
            <nuxt-link to="" class="sm:p-4 menu-link"
              >Airport transfers</nuxt-link
            >
          </li>
          <li
            class="eb-nav-menu-list text-white text-lg w-full no-underline sm:w-auto sm:p-4"
          >
            <nuxt-link to="" class="sm:p-4 menu-link">Hotel deals</nuxt-link>
          </li>
          <li
            class="eb-nav-menu-list text-white text-lg w-full no-underline sm:w-auto sm:p-4"
          >
            <nuxt-link to="" class="sm:p-4 menu-link">Car rentals</nuxt-link>
          </li>
          <li
            class="eb-nav-menu-list text-white text-lg w-full no-underline sm:w-auto sm:p-4"
          >
            <nuxt-link to="" class="sm:p-4 menu-link">Flights</nuxt-link>
          </li>
        </ul>
      </nav>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {}
  },
}
</script>
<style>
#nav-bar .eb-nav-container {
  background-color: #f70759;
}
#nav-bar .eb-nav-container .eb-nav-menu .eb-nav-menu-list .menu-link {
  color: #fff;
}
#nav-bar .eb-nav-container .eb-nav-menu .eb-nav-menu-list:hover .menu-link {
  background: #fff;
  color: #1c1a1a;
  padding-bottom: 26%;
  padding-top: 11px;
}
#nav-bar
  .eb-nav-container
  .eb-nav-menu
  .eb-nav-menu-list:hover
  .eb-nav-megamenu {
  display: block;
}
#nav-bar .eb-nav-container .eb-nav-menu .eb-nav-menu-list .eb-nav-megamenu {
  display: none;
  max-width: 100%;
  min-height: 34.25rem;
  position: absolute;
  top: 8rem;
  left: 0;
  right: 0;
  width: 100%;
  margin: 0;
  background: #fff;
  color: #d3074c;
  padding: 1.875rem 1.25rem;
  box-shadow: 1px 20px 29.7px 1px rgba(0, 0, 0, 0.1);
}
#nav-bar
  .eb-nav-container
  .eb-nav-menu
  .eb-nav-menu-list
  .eb-nav-megamenu
  .eb-brd-t {
  border-right: 0.0625rem solid #e0e0e0;
}
#nav-bar
  .eb-nav-container
  .eb-nav-menu
  .eb-nav-menu-list
  .eb-nav-megamenu
  .eb-brd-b {
  border-bottom: 0.0625rem solid #e0e0e0;
}
#nav-bar .eb-menu-icon {
  font-size: 21px;
  font-weight: 500;
}
#nav-bar
  .eb-nav-container
  .eb-nav-menu
  .eb-nav-menu-list
  .eb-nav-megamenu
  .eb-nav-megamenu-child-title {
  position: relative;
  margin-bottom: 0.6875rem;
  font-weight: 700;
  font-size: 1rem;
  color: #f70759;
  line-height: 2.3;
  text-transform: uppercase;
  overflow: visible;
  white-space: normal;
}
#nav-bar .eb-nav-container .eb-nav-third-element-link {
  color: #f70759 !important;
  font-size: 14px;
  font-weight: 200;
}
#nav-bar .o-arrow-open:before {
  content: '';
  display: block;
  width: 0.9375rem;
  height: 0.125rem;
  position: absolute;
  top: calc(50% - -0.1rem);
  right: 29px;
  background-color: #f70759;
  opacity: 0;
  -webkit-transition: right 0.7s ease-in-out, opacity 0.7s ease-in-out;
  -moz-transition: right 0.7s ease-in-out, opacity 0.7s ease-in-out;
  -o-transition: right 0.7s ease-in-out, opacity 0.7s ease-in-out;
  -ms-transition: right 0.7s ease-in-out, opacity 0.7s ease-in-out;
  transition: right 0.7s ease-in-out, opacity 0.7s ease-in-out;
}
#nav-bar .o-arrow-open {
  position: relative;
}
#nav-bar .o-arrow-open:after {
  content: '\e649';
  width: 0.75rem;
  position: absolute;
  top: 0.4rem;
  right: 0.9375rem;
  font-family: themify;
  font-size: 0.9375rem;
  color: #f70759;
  -webkit-transition: right 0.7s ease-in-out;
  -moz-transition: right 0.7s ease-in-out;
  -o-transition: right 0.7s ease-in-out;
  -ms-transition: right 0.7s ease-in-out;
  transition: right 0.7s ease-in-out;
  font-weight: 700;
}
#nav-bar .o-arrow-open:hover:before {
  right: 17px;
  opacity: 1;
}
/* #nav-bar .menu-link:before {
  content: '\B7';
  position: absolute;
  top: 0;
  left: -0.25rem;
  opacity: 0.5;
  font-size: 2.125rem;
  color: #fff;
  line-height: 1.588;
} */
</style>
