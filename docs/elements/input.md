# Input Text

```html
<label class="label">Common label</label>
<div class="input-text-wrapper">
  <input type="text" class="input-text" placeholder="placeholder text">
</div>
```

# Input Password

```html
<form class="form">
    <ul class="form-list">
        <li class="form-item">
            <div class="input-text-wrapper">
                <input type="password" class="input-text" placeholder="placeholder text">
            </div>
        </li>
        <li class="form-item">
            <div class="input-text-wrapper">
                <input type="password" class="input-text" placeholder="placeholder text">
                <meter value="33" min="0" max="100" class="password-meter is-weak" aria-label="Password strength week"></meter>
            </div>  
        </li>
        <li class="form-item">
            <div class="input-text-wrapper">
                <input type="password" class="input-text" placeholder="placeholder text">
                <meter value="66" min="0" max="100" class="password-meter is-medium" aria-label="Password strength good"></meter>
            </div> 
        </li>
        <li class="form-item">
            <div class="input-text-wrapper">
                <input type="password" class="input-text" placeholder="placeholder text">
                <meter value="100" min="0" max="100" class="password-meter is-strong" aria-label="Password strength excellent"></meter>
            </div>
        </li>
    </ul>

    
</form>
```

# Input Checkbox And Radio

```html
<input type="checkbox">
<input type="checkbox" checked>
<input type="checkbox" disabled>
<input type="checkbox" checked disabled>

<input type="radio">
<input type="radio" checked>
<input type="radio" disabled>
<input type="radio" checked disabled>
```