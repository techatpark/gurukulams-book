---
title: 'Diagram'
weight: 2
---

# Diagram

Diagram shortcode can be used as a way of displaying the images with caption.

```tpl
{{</* diagram "css-class" "caption" */>}}
**Markdown content**  
Caption
{{</* /diagram */>}}
```

## Example

{{< diagram "w-50 float-start" "Caption" >}}
```goat
┌─────┐       ┌───┐
│Alice│       │Bob│
└──┬──┘       └─┬─┘
   │            │  
   │ Hello Bob! │  
   │───────────>│  
   │            │  
   │Hello Alice!│  
   │<───────────│  
┌──┴──┐       ┌─┴─┐
│Alice│       │Bob│
└─────┘       └───┘


```  
{{< /diagram >}}

```tpl
{{</* diagram "w-50 float-end" "Caption" */>}}
```goat
┌─────┐       ┌───┐
│Alice│       │Bob│
└──┬──┘       └─┬─┘
   │            │  
   │ Hello Bob! │  
   │───────────>│  
   │            │  
   │Hello Alice!│  
   │<───────────│  
┌──┴──┐       ┌─┴─┐
│Alice│       │Bob│
└─────┘       └───┘
-```
{{</* /diagram */>}}
```