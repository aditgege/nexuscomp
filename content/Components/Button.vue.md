---
title: Button
---
# Button.vue Test edit

This component is wrapper button with several configurations

### **Setup**

component has been imported as global components

```vue
 <template>
  <n-btn
    icon
    required
  />
 </template>
```

### **Props**

| props       | type    | default | description      |
| ----------- | ------- | ------- | ---------------- |
| disabled    | Boolean | false   |                  |
| tooltip     | String  | Delete  | text tooltip     |
| icon        | Boolean | false   | button type icon |
| color       | String  | primary | color button     |
| btnIcon     | String  | ''      | icon for button  |
| loading     | Boolean | false   | icon button      |
| small       | Boolean | false   | icon type small  |
| id          | String  | ''      | id button        |
| customClass | String  | ''      | id button        |

### **Slots**

| name    | default          | descriptions    |
| ------- | ---------------- | --------------- |
| default | default vue slot | ex: text button |

- - -