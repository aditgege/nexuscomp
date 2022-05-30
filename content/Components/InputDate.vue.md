---
title: 'InputDate'
---

# InputDate.vue
This component is used to create an input date 

### **Setup**
component has been imported as global components
``` vue
 <template>
    <n-input-date
        v-model="search.start_date"
        label="Issue Date (From)"
    />
 </template>
```
### **Props**

| props | type | default | description |
| --- | --- | --- | --- |
| label | String | Date | label of input  |
| rules | Array | [] | rules |
| clearable | Booelan | true  | |
| disabled | Boolean | false |   |
| readonly | Boolean | false |  |
| prependIcon | icon | event | icon prepend input text |

* * *
