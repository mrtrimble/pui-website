---
title: Overflows
skellyCSS: true
---

{{% anchor name="Overflow" %}}

Overflow can be tricky, so we gave you as much as we could.

{{< classes result="true" >}}
{{< classes-row class="overflow-visible" result="Sets overflow to visible." >}}
{{< classes-row class="overflow-hidden" result="Sets overflow to hidden." >}}
{{< classes-row class="overflow-scroll" result="Sets overflow to scroll." >}}
{{< classes-row class="overflow-auto" result="Sets overflow to auto." >}}
{{< classes-row class="overflow-y--visible" result="Sets overflow to visible." >}}
{{< classes-row class="overflow-y--hidden" result="Sets overflow to hidden." >}}
{{< classes-row class="overflow-y--scroll" result="Sets overflow to scroll." >}}
{{< classes-row class="overflow-y--auto" result="Sets overflow to auto." >}}
{{< classes-row class="overflow-x--visible" result="Sets overflow to visible." >}}
{{< classes-row class="overflow-x--hidden" result="Sets overflow to hidden." >}}
{{< classes-row class="overflow-x--scroll" result="Sets overflow to scroll." >}}
{{< classes-row class="overflow-x--auto" result="Sets overflow to auto." >}}
{{< /classes >}}

<div class="block-container">
    <div class="block laptop-up-6 overflow-y--hidden">
        <button class="button button-primary background--salmon text--white overflow-button">Toggle Overflow</button>
        <div class="mt-2 mb-7 p-3 border border--color-med-blue overflow-paragraph" style="height: 7rem;">
            <h2 class="skeleton skeleton--md" role="presentation"></h2>
            <p class="skeleton" data-lines="5" role="presentation"></p>
            <p class="skeleton" data-lines="3" role="presentation"></p>
            <p class="skeleton" data-lines="6" role="presentation"></p>
        </div>
    </div>
</div>