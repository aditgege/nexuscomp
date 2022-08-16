---
title: InputOtherExpense
---
# InputOtherExpense.vue

This component is used to create an  input misch charges with several option and add form

### **Setup**

component has been imported as global components

```javascript
 <template>
  <n-input-misc
      v-model="request.misc_charges"
      solo
      @change="calculateInboundLogistic"
  />
 </template>
```

### **Props**

| props       | type           | default                 | description |
| ----------- | -------------- | ----------------------- | ----------- |
| value       | String, Number |                         |             |
| appendIcon  | String         | ''                      |             |
| label       | String         | Choose Business partner |             |
| disable     | Boolean        | false                   |             |
| readonly    | Boolean        | false                   |             |
| loading     | Boolean        | false                   |             |
| rules       | Boolean        | false                   |             |
|       solo      |                |                         |             |

- - -

#### events:
`@change`\
`@input`\