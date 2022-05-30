---
title: 'InputAccount'
---

# InputAccount.vue
This component is used to create an  select input account 

### **Setup**
component has been imported as global components
``` vue
 <template>
  <n-input-account
        v-model="request.account_id"
        required
    />
 </template>
```
### **Props**

| props | type | default | description |
| --- | --- | --- | --- |
| label | String | Chart of Account | label of input  |
| rules | Array | [] | rules |
| clearable | Booelan | true  | |
| disabled | Boolean | false |   |
| readonly | Boolean | false |  |
| prependIcon | icon | mdi-cash-register | icon prepend input text |
| required | Boolean | true | set field to required |
| required | Boolean | true | set field to required |
| itemText | String | name | name field displayed on list |
| itemValue | String | systemid | selected value field |
| returnObject | Boolean | false | return selected Object |
| isActive | Boolean | true | filter account with status is active  |
| isBank | Boolean | false | filter account with account category bank |





* * *
