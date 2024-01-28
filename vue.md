### Scafold vue functional component (script setup)

```
"	Scafold vue functional component": {
	"prefix": "sct",
	"body": [
		"<script setup lang=\"ts\"></script>",
		"<template>$TM_FILENAME_BASE</template>"
	],
	"description": "Vue 3 Single-File Component with TypeScript"
},
```

### Scafold vue functional component (otpions api)

```
	"Vue Single-File Component Template": {
	"prefix": "scto",
	"body": [
		"<template>",
		"  ",
		"</template>",
		"<script>",
		"export default {",
		"  components: {},",
		"  data() {",
		"    return {};",
		"  },",
		"  computed: {",
		"  }",
		"};",
		"</script>"
	],
	"description": "Vue Single-File Component Template"
},

```

### Ref

```
"Create ref with variable name": {
		"prefix": "reff",
		"body": [
			"const $1 = ref($2)$0",
		],
		"description": "Create ref with variable name"
	},
```

### Ref type string

```
	"Create ref string with variable name": {
		"prefix": "refs",
		"body": [
			"const $1 = ref<string>($2)$0",
		],
		"description": "Create ref string with variable name"
	},
```

### Ref type number

```
	"Create ref number with variable name": {
		"prefix": "refn",
		"body": [
			"const $1 = ref<number>($2)$0",
		],
		"description": "Create ref number with variable name"
	},
```

### Ref type number

```
	"Create ref boolean with variable name": {
		"prefix": "refb",
		"body": [
			"const $1 = ref<boolean>($2)$0",
		],
		"description": "Create ref boolean with variable name"
	},

```

### Computed

```
	"cpComputed": {
		"prefix": "cp",
		"body": [
			"const $1 = computed(() => {",
			"\t$2",
			"});"
		],
		"description": "Create a computed property"
	},
```
