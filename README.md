# parallel
A living table to draw parallels between languages

## Why

Often when I try to explore another language, I find myself trying to draw parallels (hence the name) to things that I am already familiar with. This way makes it easier for me to wrap my head around new workflows and concepts and speeds up adoption time.

<br/>

## Languages

### Workflow

| Language | Version Manager | Package Manager |
| -------- | --------------- | --------------- |
| Go | Integrated |  |
| JS/TS | nvm | npm, yarn |
| Python | pyenv | pip |
| Rust |  | cargo |

<br />

### Syntax

#### Function declaration

**TypesScript**
```ts
function Walk(p: Person) {}
```

**Go**
```go
func (p person) walk() {}
```


<br/>

### Concurrency/Parallelism
**TypeScript**

Concurrency
```ts 
async
```

```go
defer
```
Executes once surrounding function returns.

<br/>
<br/>

## Contributing

This is a very fresh project, so no guidelines as of date. Just submit a PR!
