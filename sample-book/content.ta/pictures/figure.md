# Figure

Figure shortcode can be used as a way of displaying the images with caption.

```tpl
{{</* figure "[path]" "css-class" */>}}
**Markdown content**  
Caption
{{</* /figure */>}}
```

## Example

{{< figure "figure.jpeg" "w-50 float-end" >}}
**Figure with 50%**  
{{< /figure >}}

```tpl
{{</* figure "figure.jpeg" "w-50 float-end" */>}}
**Figure with 50%**
{{</* /figure */>}}
```