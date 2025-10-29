import -

```jsx
import {
  InputGroup,
  InputGroupAddon,
  InputGroupButton,
  InputGroupInput,
  InputGroupText,
  InputGroupTextarea,
} from "@/components/ui/input-group"
```

---

default -

```jsx
<InputGroup>
  <InputGroupInput placeholder="Search..." />
  <InputGroupAddon>
    <SearchIcon />
  </InputGroupAddon>
  <InputGroupAddon align="inline-end">
    <InputGroupButton>Search</InputGroupButton>
  </InputGroupAddon>
</InputGroup>
```

---

icon -

```jsx
<InputGroup>
  <InputGroupInput placeholder="Card number" />
  <InputGroupAddon>
    <CreditCardIcon />
  </InputGroupAddon>
  <InputGroupAddon align="inline-end">
    <CheckIcon />
  </InputGroupAddon>
</InputGroup>
```

---

button -

```jsx
<InputGroup>
  <InputGroupInput placeholder="Type to search..." />
  <InputGroupAddon align="inline-end">
    <InputGroupButton variant="secondary">Search</InputGroupButton>
  </InputGroupAddon>
</InputGroup>
```

---

tooltip -

```jsx
<InputGroup>
  <InputGroupInput placeholder="Enter password" type="password" />
  <InputGroupAddon align="inline-end">
    <Tooltip>
      <TooltipTrigger asChild>
        <InputGroupButton variant="ghost" aria-label="Info" size="icon-xs">
          <InfoIcon />
        </InputGroupButton>
      </TooltipTrigger>
      <TooltipContent>
        <p>Password must be at least 8 characters</p>
      </TooltipContent>
    </Tooltip>
  </InputGroupAddon>
</InputGroup>
```

