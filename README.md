# NuxtUI.Snippets 


## 📄`app.vue`
* **Prefix:** `!`
* **Body:**
  ```vue
  <template>
    <UApp>
      <NuxtLayout>
        <NuxtPage />
      </NuxtLayout>
    </UApp>
  </template>
  ```
* **Discription:** `/app/app.vue`


## 📄`layouts/default.vue`
* **Prefix:** `!!`
* **Body:**
  ```vue
  <template>
    <div>
      <UHeader />

      <UMain>
        <slot />
      </UMain>

      <UFooter />
    </div>
  </template>
  ```
* **Discription:** `/app/layouts/default.vue`