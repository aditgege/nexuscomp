---
title: 'IndexTemplate'
---

# IndexTemplate.vue
This component is used to create a common index page with several configurations

### **Setup**
component has been imported as global components
``` vue
 <template>
    <n-index-template 
      ref="indexTable"
      title="some title"
      title-color="title color"
      :table-headers="headers"
      :search="search"
      repository="someRepo"
      @click:refresh="search = {}"
      @click:add="someaction"
    >
      <template #search>
        // search component
      <template>
      <template #item="props">
        // some element table item, props is object with data
      </template>
    </n-index-template>
 </template>
```
### **Props**

| props | type | default | description |
| --- | --- | --- | --- |
| title | String | Title index Page | Title on top of table |
| tableHeaders | Array | `[ { text: String, align: String (left, right, center), sortable: Boolean, value: String } ]` | headers table  |
| search | Object | {}  | object search with  key value { name: 'test' } format |
| repository | String |     |  repository name in repositorifactory.js |
| titleColor | String | green--text | title color with vuetify naming class |
| alert | Object | { show: false, color: undefined, message} | object alert |

### **function**

`refresh()`: refresh table

use with refs
``` javascript
this.$refs.indexTable.refresh()
```

### **Slots**

| name | default | description |
| --- | --- | --- |
| search | - | use this slot for override search component on top page |
| item | table item | use this slot for override item table |

### **Events**

::list
- **@click:add** event will be triggered when user click add button
- **@click:refresh** event will be triggered when user click refresh button
::
* * *
