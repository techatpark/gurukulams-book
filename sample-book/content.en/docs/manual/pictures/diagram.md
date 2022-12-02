# Diagram

Diagram shortcode can be used as a way of displaying the images with caption.

```tpl
{{</* diagram "[path]" "css-class" */>}}
**Markdown content**  
Caption
{{</* /diagram */>}}
```

## Example

{{< diagram "diagram1.jpeg" "w-50 float-end" >}}
**Diagram with 50%**  
{{< /diagram >}}

```tpl
{{</* diagram "diagram.jpeg" "w-50 float-end" */>}}
**Diagram with 50%**
{{</* /diagram */>}}
```