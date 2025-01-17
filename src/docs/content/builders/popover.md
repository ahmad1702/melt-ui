---
title: Popover
description: Displays rich content in a portal, triggered by a button.
---

<script>
    import { APIReference, KbdTable } from '$docs/components' 
    export let schemas
    export let keyboard
</script>

## Anatomy

- **Trigger**: The button(s) which open/close the popover.
- **Content**: The content area viewed when the trigger is clicked.
- **Arrow**: An optional arrow component
- **Close**: A button which closes the popover

## Usage

To create a popover, use the `createPopover` builder function. Follow the anatomy or the example
above to create your popover.

## API Reference

<APIReference {schemas} />

## Accessibility

Adheres to the
[Dialog WAI-ARIA design pattern](https://www.w3.org/WAI/ARIA/apg/patterns/dialogmodal)

<KbdTable {keyboard} />
