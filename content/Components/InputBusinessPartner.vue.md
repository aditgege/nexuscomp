---
title: InputBusinessPartner
---
# InputBusinessPartner.vue

This component is used to create an  input business contact

### **Setup**

component has been imported as global components

```javascript
 <template>
  <n-input-businesspartner
      v-model="search.vendor_id"
      label="Vendor Name"
      prepend-icon="mdi-domain"
      :is-customer="false"
  />
 </template>
```

### **Props**

| props       | type           | default                 | description |
| ----------- | -------------- | ----------------------- | ----------- |
| value       | String, Number |                         |             |
| prependIcon | String         | mdi-call-merge          |             |
| appendIcon  | String         | ''                      |             |
| label       | String         | Choose Business partner |             |
| disable     | Boolean        | false                   |             |
| readonly    | Boolean        | false                   |             |
| loading     | Boolean        | false                   |             |
| rules       | Boolean        | false                   |             |
| prependIcon | Array          | mdi-map-marker          |             |
| isCustomer  | Boolean        | true                    |             |
| isVendor    | Boolean        | true                    |             |

- - -

#### events:\
\
`@change`\
`@input`\
`@click:append`