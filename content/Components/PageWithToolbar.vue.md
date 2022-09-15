---
title: PageWithToolbar
---
# PageWithToolbar.vue

This component is used to create a common add and edit page with several configurations

### **Setup**

```vue
<template>
  <n-page-with-toolbar
      :is-valid="Boolean"
      :breadcrumbs="breadcrumbs"
      :loading="Boolean"
      :print-props="{
          name: "nameFile",
          url: "endpoint print"
      }"
      @click:save="function"
      @click:reset="function"
      @click:cancel="function"
    >
    // content
  </n-page-with-toolbar>
</template>
```

### **Props**

| props         | type    | default                                                                          | descriptions                                                                          |
| ------------- | ------- | -------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| noBreadcrumbs | String  | false                                                                            | if page not use breadcrubms                                                           |
| breadcrubms   | Array   | `[ { text:  'Dashboard', disabled:  false, href:  'breadcrumbs_dashboard', }, ]` | array breadcrubms                                                                     |
| isValid       | Boolean | false                                                                            |                                                                                       |
| title         | String  |                                                                                  | title on top left page (if not use breadcrubms)                                       |
| color         | String  | green--text                                                                      | change title color, format naming class vuetify                                       |
| loading       | Boolean | false                                                                            | loading on save                                                                       |
| printProps    | Object  | `{ name: 'data', url:''}`                                                        | props untuk menampilkan button print , di tambah jika memang membutuhkan button print |

### **function**

::list

* refresh(): refresh table
  ::

```javascript
this.$refs.pageWithToolbar.refresh()
```

### **Slots**

| name    | default          | descriptions |
| ------- | ---------------- | ------------ |
| default | default vue slot |              |