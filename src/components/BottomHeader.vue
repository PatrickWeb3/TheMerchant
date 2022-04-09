<template>
  <Disclosure as="nav" class="shadow" v-slot="{ open }">
    <div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-8">
      <div class="relative flex justify-between h-16">
        <div class="absolute inset-y-0 left-0 flex items-center md:hidden">
          <!-- Mobile menu button -->
          <DisclosureButton class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-blue-400">
            <span class="sr-only">Open main menu</span>
            <MenuIcon v-if="!open" class="block h-6 w-6" aria-hidden="true" />
            <XIcon v-else class="block h-6 w-6" aria-hidden="true" />
          </DisclosureButton>
        </div>
        <div class="flex-1 flex items-center justify-center md:items-stretch md:justify-start">
          <div class="flex-shrink-0 flex items-center">
              <span class="flex text-gray-700 sm:ml-24 md:ml-0">
                  <ShieldCheckIcon class="block lg:hidden h-7 w-auto mt-0.5 mr-1" />
                  <h2 class="block lg:hidden h-8 w-auto text-xl uppercase font-semibold">The Merchant</h2>
              </span>
              <span class="flex text-gray-700">
                  <ShieldCheckIcon class="hidden lg:block h-7 w-auto mt-0.5 mr-1" />
                  <h2 class="hidden lg:block h-8 w-auto text-xl uppercase font-semibold">The Merchant</h2>
              </span>
          </div>
          <div class="hidden sm:ml-6 lg:-ml-20 md:ml-0 md:flex sm:space-x-8 w-full justify-center">
            <!-- Current: "border-indigo-500 text-gray-900", Default: "border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700" -->
            <a href="#" class="border-blue-400 text-gray-900 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium"> Shop </a>
            <a href="#" class="border-transparent text-gray-500 hover:border-blue-400 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium"> On Sale </a>
            <a href="#" class="border-transparent text-gray-500 hover:border-blue-400 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium"> Affiliates </a>
            <a href="#" class="border-transparent text-gray-500 hover:border-blue-400 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium"> FAQ's </a>
            <a href="#" class="border-transparent text-gray-500 hover:border-blue-400 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium"> Blog </a>
          </div>
        </div>
        <div class="absolute inset-y-0 right-0 flex items-center md:pr-2 sm:static sm:inset-auto sm:ml-6 sm:pr-0">
          <button type="button" class="bg-white p-1 rounded-full text-gray-500 hover:text-gray-400">
            <span class="sr-only">View notifications</span>
            <BellIcon class="h-7 w-7" aria-hidden="true" />
          </button>

          <!-- Profile dropdown -->
          <Menu as="div" class="ml-3 relative">
            <div>
              <MenuButton class="bg-white rounded-full flex text-sm text-gray-700">
                <span class="sr-only">Open user menu</span>
                <UserCircleIcon class="text-gray-500 focus:text-gray-700 hover:text-gray-400 h-7 w-7 rounded-full" aria-hidden="true" />
              </MenuButton>
            </div>
            <transition enter-active-class="transition ease-out duration-200" enter-from-class="transform opacity-0 scale-95" enter-to-class="transform opacity-100 scale-100" leave-active-class="transition ease-in duration-75" leave-from-class="transform opacity-100 scale-100" leave-to-class="transform opacity-0 scale-95">
              <MenuItems class="origin-top-right absolute right-0 mt-2 w-48 rounded-md shadow-lg py-1 bg-white ring-1 ring-black ring-opacity-5 focus:outline-none">
                <MenuItem v-slot="{ active }">
                  <a href="#" :class="[active ? 'bg-gray-100' : '', 'block px-4 py-2 text-sm text-gray-700']">Your Profile</a>
                </MenuItem>
                <MenuItem v-slot="{ active }">
                  <a href="#" :class="[active ? 'bg-gray-100' : '', 'block px-4 py-2 text-sm text-gray-700']">Settings</a>
                </MenuItem>
                <MenuItem v-slot="{ active }">
                  <a href="#" :class="[active ? 'bg-gray-100' : '', 'block px-4 py-2 text-sm text-gray-700']">Sign out</a>
                </MenuItem>
              </MenuItems>
            </transition>
          </Menu>
        </div>
      </div>
    </div>

    <DisclosurePanel class="md:hidden">
      <div class="pt-2 pb-4 space-y-1">
        <!-- Current: "bg-indigo-50 border-indigo-500 text-indigo-700", Default: "border-transparent text-gray-500 hover:bg-gray-50 hover:border-gray-300 hover:text-gray-700" -->
        <DisclosureButton as="a" href="#" class="bg-blue-50 border-blue-400 text-blue-500 block pl-3 pr-4 py-2 border-l-4 text-base font-medium">Shop</DisclosureButton>
        <DisclosureButton as="a" href="#" class="border-transparent text-gray-500 hover:bg-gray-50 hover:border-gray-300 hover:text-gray-700 block pl-3 pr-4 py-2 border-l-4 text-base font-medium">On Sale</DisclosureButton>
        <DisclosureButton as="a" href="#" class="border-transparent text-gray-500 hover:bg-gray-50 hover:border-gray-300 hover:text-gray-700 block pl-3 pr-4 py-2 border-l-4 text-base font-medium">Affiliates</DisclosureButton>
        <DisclosureButton as="a" href="#" class="border-transparent text-gray-500 hover:bg-gray-50 hover:border-gray-300 hover:text-gray-700 block pl-3 pr-4 py-2 border-l-4 text-base font-medium">FAQ's</DisclosureButton>
        <DisclosureButton as="a" href="#" class="border-transparent text-gray-500 hover:bg-gray-50 hover:border-gray-300 hover:text-gray-700 block pl-3 pr-4 py-2 border-l-4 text-base font-medium">Blog</DisclosureButton>
      </div>
    </DisclosurePanel>
  </Disclosure>
</template>

<script>
import { Disclosure, DisclosureButton, DisclosurePanel, Menu, MenuButton, MenuItem, MenuItems, } from '@headlessui/vue'
import { BellIcon, MenuIcon, XIcon, UserCircleIcon, ShieldCheckIcon } from '@heroicons/vue/outline'

export default {
  components: {
    Disclosure,
    DisclosureButton,
    DisclosurePanel,
    Menu,
    MenuButton,
    MenuItem,
    MenuItems,
    BellIcon,
    MenuIcon,
    XIcon,
    UserCircleIcon,
    ShieldCheckIcon,
  },
}
</script>