---
title: InputNumber
---
# InputNumber.vue

This component is used to create an  input number with thousand separator

### **Setup**

component has been imported as global components

```javascript
 <template>
 <n-input-number
    v-model="request.amount"
    label="Amount*"
    icon="mdi-counter"
    :rules="[rules.required, rules.cantzero]"
    placeholder="0"
    :onkeypress="'false'"
  /> 
 </template>
```

### **Props**

| props       | type           | default                 | description |
| ----------- | -------------- | ----------------------- | ----------- |
| id | String|            0             |             |
| placeholder| String|                         |             |
| icon | String|                         |             |
| flat| Boolean|             true           |             |
| solo| Boolean|             false|             |
| clearable| Boolean|             false|             |
| lazy| Boolean|             false|     will validate rules on blur        |
| value       | String, Number |                         |             |
| prependIcon | String         | mdi-call-merge          |             |
| appendIcon  | String         | ''                      |             |
| label       | String         | Choose Business partner |             |
| disabled     | Boolean        | false                   |             |
| readonly    | Boolean        | false                   |             |
| loading     | Boolean        | false                   |             |
| rules       | Boolean        | false                   |             |
| prependIcon | Array          | mdi-map-marker          |             |
| isCustomer  | Boolean        | true                    |             |
| isVendor    | Boolean        | true                    |             |

- - -

#### events:
`@change`\
`@input`\
`@click`\
`@focus`\
`@blur`\
`@click:append`\
`@click:append`