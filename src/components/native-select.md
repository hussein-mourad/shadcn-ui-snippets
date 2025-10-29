import -

```jsx
import {
  NativeSelect,
  NativeSelectOptGroup,
  NativeSelectOption,
} from "@/components/ui/native-select"
```

---

default -

```jsx
<NativeSelect>
  <NativeSelectOption value="">Select a fruit</NativeSelectOption>
  <NativeSelectOption value="apple">Apple</NativeSelectOption>
  <NativeSelectOption value="banana">Banana</NativeSelectOption>
  <NativeSelectOption value="blueberry">Blueberry</NativeSelectOption>
  <NativeSelectOption value="grapes" disabled>
    Grapes
  </NativeSelectOption>
  <NativeSelectOption value="pineapple">Pineapple</NativeSelectOption>
</NativeSelect>
```

---

disabled -

```jsx
<NativeSelect disabled>
  <NativeSelectOption value="">Select priority</NativeSelectOption>
  <NativeSelectOption value="low">Low</NativeSelectOption>
  <NativeSelectOption value="medium">Medium</NativeSelectOption>
  <NativeSelectOption value="high">High</NativeSelectOption>
  <NativeSelectOption value="critical">Critical</NativeSelectOption>
</NativeSelect>
```

---

invalid -

```jsx
<NativeSelect aria-invalid="true">
  <NativeSelectOption value="">Select role</NativeSelectOption>
  <NativeSelectOption value="admin">Admin</NativeSelectOption>
  <NativeSelectOption value="editor">Editor</NativeSelectOption>
  <NativeSelectOption value="viewer">Viewer</NativeSelectOption>
  <NativeSelectOption value="guest">Guest</NativeSelectOption>
</NativeSelect>
```
