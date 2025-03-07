---
title: Flexbox
description: Documentation for Platform UI's flexbox components and utilities.
---
{{% anchor name="display" %}}

Our flex utilities are easy to use, and fairly comprehensive. The only property you need in place to start unlocking the power of flexbox is `display: flex`, or `display: inline-flex` if you have a use case. 

{{< classes attr="true">}}
{{< classes-row class="flex" attr="display: flex" >}}
{{< classes-row class="flex-inline" attr="display: flex-inline" >}}
{{< /classes >}}

{{< callout header="the exception">}}
`flex--center-content`, under [Content](#content) is the only flex utility that **DOES NOT** require the initial `flex` class. `display: flex` is already set.
{{< /callout >}}
{{% anchor name="align" %}}
Sets the flex container to align all contained elements to either the start, center, end, or baseline points of the container.

{{< visualizer header="Click the buttons below to toggle the flex align utility classes!" >}}
<div class="actions block">
  <ul class="list">
    <li>
      <button class="button" data-example-container="flex--align-start">
        <pre>.flex--align-start</pre>
      </button>
    </li>
    <li>
      <button class="button" data-example-container="flex--align-center">
        <pre>.flex--align-center</pre>
      </button>
    </li>
    <li>
      <button class="button" data-example-container="flex--align-end">
        <pre>.flex--align-end</pre>
      </button>
    </li>
    <li>
      <button class="button" data-example-container="flex--align-baseline">
        <pre>.flex--align-baseline</pre>
      </button>
    </li>
    <li>
      <button class="button button--salmon text--white" data-reset="true">
        Reset
      </button>
    </li>
  </ul>
</div>
<div class="results rounded-2 block background--dark p-3" data-setup='{"classes":["flex vh-25"],"children":[{"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]},{"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}]}'>
</div>
{{< /visualizer >}}

{{% anchor name="align-self" %}}
Sets individual elements to align to either the start, center, end, or baseline points of a flex container.

{{< visualizer header="Click the buttons below to toggle the flex align-self utility classes!" >}}
<div class="actions block">
  <ul class="list">
    <li>
      <button class="button" data-example-elements="flex--align-self-start">
        <pre>.flex--align-self-start</pre>
      </button>
    </li>
    <li>
      <button class="button" data-example-elements="flex--align-self-center">
        <pre>.flex--align-self-center</pre>
      </button>
    </li>
    <li>
      <button class="button" data-example-elements="flex--align-self-end">
        <pre>.flex--align-self-end</pre>
      </button>
    </li>
    <li>
      <button class="button" data-example-elements="flex--align-self-baseline">
        <pre>.flex--align-self-baseline</pre>
      </button>
    </li>
    <li>
      <button class="button button--salmon text--white" data-reset="true">
        Reset
      </button>
    </li>
  </ul>
</div>
<div class="results rounded-2 block background--dark p-3" data-setup='{"classes":["flex vh-25"],"children":[{"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]},{"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}]}'>
</div>
{{</ visualizer >}}

{{% anchor name="justify" %}}
Sets individual elements to align to either the start, center, end, or baseline points of a flex container.

{{< visualizer header="Click the buttons below to toggle the flex justify utility classes!" >}}
<div class="actions block">
  <ul class="list">
    <li>
      <button class="button" data-example-container="flex--justify-start">
        <pre>.flex--justify-start</pre>
      </button>
    </li>
    <li>
      <button class="button" data-example-container="flex--justify-center">
        <pre>.flex--justify-center</pre>
      </button>
    </li>
    <li>
      <button class="button" data-example-container="flex--justify-end">
        <pre>.flex--justify-end</pre>
      </button>
    </li>
    <li>
      <button class="button" data-example-container="flex--justify-around">
        <pre>.flex--justify-around</pre>
      </button>
    </li>
    <li>
      <button class="button" data-example-container="flex--justify-between">
        <pre>.flex--justify-between</pre>
      </button>
    </li>
    <li>
      <button class="button button--salmon text--white" data-reset="true">
        Reset
      </button>
    </li>
  </ul>
</div>
<div class="results rounded-2 block background--dark p-3" data-setup='{"classes":["flex vh-25"],"children":[{"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]},{"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}]}'>
</div>
{{< /visualizer >}}

{{% anchor name="direction" %}}
Utility classes to handle the direction of elements within a flex container.

{{< visualizer header="Click the buttons below to toggle the direction utility classes!" >}}
<div class="actions block">
  <ul class="list">
    <li>
      <button class="button" data-example-container="flex--row-reverse">
        <pre>.flex--row-reverse</pre>
      </button>
    </li>
    <li>
      <button class="button" data-example-container="flex--column">
        <pre>.flex--flex-column</pre>
      </button>
    </li>
    <li>
      <button class="button" data-example-container="flex--column-reverse">
        <pre>.flex--column-reverse</pre>
      </button>
    </li>
    <li>
      <button class="button button--salmon text--white" data-reset="true">
        Reset
      </button>
    </li>
  </ul>
</div>
<div class="results rounded-2 block background--dark p-3" data-setup='{"classes":["flex vh-25"],"children":[{"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]},{"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}]}'>
</div>
{{< /visualizer >}}

{{% anchor name="content" %}}
Utility classes to handle wrapping, spacing, and centering of content within a flex container.

{{< visualizer header="Click the buttons below to toggle the content utility classes!" >}}
<div class="block-12 tabs my-4">
  <input type="radio" id="flex-wrap" name="tabs" checked>
  <label for="flex-wrap" class="tab">
    Wrap
  </label>
  <div class="tab-panel">
    <div class="visualizer block-container p-3 py-4 tablet-up-2 my-4">
      <div class="actions block">
        <ul class="list">
          <li>
            <button class="button" data-example-container="flex--nowrap">
              <pre>.flex--nowrap</pre>
            </button>
          </li>
          <li>
            <button class="button" data-example-container="flex--wrap">
              <pre>.flex--wrap</pre>
            </button>
          </li>
          <li>
            <button class="button button--salmon text--white" data-reset="true">
              Reset
            </button>
          </li>
        </ul>
      </div>
      <div class="results rounded-2 block background--dark p-3" data-setup='{"classes":["flex vh-25"],"children":[{"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}]}'>
      </div>
    </div>
  </div>

  <input type="radio" id="flex-grow" name="tabs">
  <label for="flex-grow" class="tab">
    Grow
  </label>
  <div class="tab-panel">
    <div class="visualizer block-container p-3 py-4 tablet-up-2 my-4">
      <div class="actions block">
        <ul class="list">
          <li>
            <button class="button" data-example-elements="flex--grow">
              <pre>.flex--grow</pre>
            </button>
          </li>
          <li>
            <button class="button button--salmon text--white" data-reset="true">
              Reset
            </button>
          </li>
        </ul>
      </div>
      <div class="results rounded-2 block background--dark p-3" data-setup='{"classes":["flex", "vh-25"],"children":[{"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}]}'>
      </div>
    </div>
  </div>

  <input type="radio" id="flex-center" name="tabs">
  <label for="flex-center" class="tab">
    Center
  </label>
  <div class="tab-panel">
    <div class="visualizer block-container p-3 py-4 tablet-up-2 my-4">
      <div class="actions block">
        <ul class="list">
          <li>
            <button class="button" data-example-container="flex--center-content">
              <pre>.flex--center-content</pre>
            </button>
          </li>
          <li>
            <button class="button button--salmon text--white" data-reset="true">
              Reset
            </button>
          </li>
        </ul>
      </div>
      <div class="results rounded-2 block background--dark p-3" data-setup='{"classes":["flex", "vh-25"],"children":[{"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}, {"el":"div","classes":["abstract-element", "background--light-purple", "border", "border--color-white"]}]}'>
      </div>
    </div>
  </div>
</div>
{{< /visualizer >}}