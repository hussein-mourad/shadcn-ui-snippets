import -

```jsx
import {
  ButtonGroup,
  ButtonGroupSeparator,
  ButtonGroupText,
} from "@/components/ui/button-group"
```

---

default -

```jsx
<ButtonGroup>
  <Button>Button 1</Button>
  <Button>Button 2</Button>
</ButtonGroup>
```

---

vertical -

```jsx
<ButtonGroup
  orientation="vertical"
  aria-label="Media controls"
  className="h-fit"
>
  <Button variant="outline" size="icon">
    <PlusIcon />
  </Button>
  <Button variant="outline" size="icon">
    <MinusIcon />
  </Button>
</ButtonGroup>
```
