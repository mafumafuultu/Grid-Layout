# GridLayout

![licence](https://img.shields.io/badge/license-MIT-blue.svg)

シンプルなGridの実装。


## Use
```html
<div class="grid-12">
	<div class="g-1-12"> 1 of 12 </div>
	<div class="g-2-12"> 2 of 12 </div>
	<div class="g-3-12"> 3 of 12 </div>
	<div class="g-4-12"> 4 of 12 </div>
	<div class="g-5-12"> 5 of 12 </div>
</div>

<div class="grid-24">
	<div class="g-1-24"> 1 of 24 </div>
	<div class="g-2-24"> 2 of 24 </div>
	<div class="g-3-24"> 3 of 24 </div>
	<div class="g-4-24"> 4 of 24 </div>
	<div class="g-5-24"> 5 of 24 </div>
</div>
```

## Customize

```less
@gridColumnSplit : 2, 4, 5, 7, 9, 12, 16, 24;
@gridGap : 8px;
@gridRowBaseSize : 24px;
```

