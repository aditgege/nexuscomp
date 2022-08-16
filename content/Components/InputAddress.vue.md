---
title: InputAddress
---
# InputAddress.vue

This component is used to create an  input address business contact

### **Setup**

component has been imported as global components

```javascript
 <template>
  <n-input-address
      v-model="request.vendor_address"
      label="Vendor Address"
      type="purchase"
      :bussiness_partnerid="request.vendor_id"
  />
 </template>
```

### **Props**

| props  | type | default | description |
| ------ | ---- | ------- | ----------- |
| value  |   String, Number   |         |             |
| prependIcon |   String |     mdi-map-marker    |             |
| appendIcon |   String |    mdi-magnify   |             |
| label |String|Customer Address||
| type |   String |     sales    |             |
| disable|   Boolean |     false    |             |
| readonly |   Boolean |     false    |             |
| loading |   Boolean |     false   |             |
| bussiness_partnerid|   String |    null   |             |
| rules |   Boolean|     false    |             |
| prependIcon |   Array|     mdi-map-marker    |             |



- - -