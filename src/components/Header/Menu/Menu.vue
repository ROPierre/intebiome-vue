<template src="./Menu.html"></template>

<script>
export default {
  name: 'top-menu',
  props: ['showMenu'],
  data() {
    return {
      links: [
        {
          category: 'about us',
          submenu: [
            {
              name: 'brand philosophy',
              link: '#',
            },
            {
              name: 'product tecnology',
              link: '#',
            },
          ],
          link: '',
        },
        {
          category: 'our products',
          submenu: [
            {
              name: 'all products',
              link: '#',
            },
            {
              name: 'intibiome wellness',
              link: '#',
            },
          ],
          link: '',
        },
        {
          category: 'intimate health',
          submenu: [
            {
              name: 'article 1',
              link: '#',
            },
            {
              name: 'article 2',
              link: '#',
            },
            {
              name: 'article 3',
              link: '#',
            },
            {
              name: 'faq',
              link: '#',
            },
          ],
          link: '',
        },
        {
          category: 'contact us',
          submenu: [],
          link: '#',
        },
      ],
      submenus: [],
      isOpenSubmenu: false,
    };
  },
  methods: {
    getMenu(menu) {
      const submenus = this.links.filter((item) => item.category === menu);
      this.submenus = submenus[0].submenu;
      this.isOpenSubmenu = true;
    },
  },
};
</script>

<style src="./Menu.css"></style>
