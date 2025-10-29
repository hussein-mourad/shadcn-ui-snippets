import -

```jsx
import {
  Item,
  ItemActions,
  ItemContent,
  ItemDescription,
  ItemFooter,
  ItemHeader,
  ItemMedia,
  ItemTitle,
} from "@/components/ui/item"
```

---

default -

```jsx
<Item>
  <ItemHeader>Item Header</ItemHeader>
  <ItemMedia />
  <ItemContent>
    <ItemTitle>Item</ItemTitle>
    <ItemDescription>Item</ItemDescription>
  </ItemContent>
  <ItemActions />
  <ItemFooter>Item Footer</ItemFooter>
</Item>
```

---

outline -

```jsx
<Item variant="outline">
  <ItemContent>
    <ItemTitle>Outline Variant</ItemTitle>
    <ItemDescription>
      Outlined style with clear borders and transparent background.
    </ItemDescription>
  </ItemContent>
  <ItemActions>
    <Button variant="outline" size="sm">
      Open
    </Button>
  </ItemActions>
</Item>
```

---

muted -

```jsx
<Item variant="muted">
  <ItemContent>
    <ItemTitle>Muted Variant</ItemTitle>
    <ItemDescription>
      Subdued appearance with muted colors for secondary content.
    </ItemDescription>
  </ItemContent>
  <ItemActions>
    <Button variant="outline" size="sm">
      Open
    </Button>
  </ItemActions>
</Item>
```

---

link -

```jsx
<Item asChild>
  <a href="">
    <ItemContent>
      <ItemTitle>Visit our documentation</ItemTitle>
      <ItemDescription>
        Learn how to get started with our components.
      </ItemDescription>
    </ItemContent>
    <ItemActions>
      <ChevronRightIcon className="size-4" />
    </ItemActions>
  </a>
</Item>
```
