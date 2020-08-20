# React Dropdown

> A small personal library for react.

### Dependency

##### Note: This library is only for React.

-  react-router-dom

### Usuage

Clone only Dropdown branch into your Components folder
`git clone --branch Dropdown https://github.com/arun-praj/my-react-library.git`
| Component | Props | Description |
| ----------- | ---------- |-------------|
| Dropdown | botton | |
| Dropgroups | - | Groups links |
| DropLink | value, to |Links |

### Example

```javascript
import { Dropdown, Dropgroup, DropLink } from "./your_path_to_Dropdown/Dropdown";

<Dropdown button={<button>Hover Me</button>}>
   <Dropgroups>
      <DropLink value='Link 1' to='/link1' />
      <DropLink value='Link 2' />
      <DropLink value='Link 3' />
   </Dropgroups>
   <Dropgroups>
      <DropLink value='Link 4' to='/link1' />
   </Dropgroups>
</Dropdown>;
```
<img src="https://ibb.co/C1ygzvZ" title="FVCproductions" alt="FVCproductions">
