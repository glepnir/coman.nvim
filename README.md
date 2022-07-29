<center>
<h1><p> Comment and Annotation </p></h1>
</center>

## Install

```lua
packer.use('glepnir/coman.nvim')
```

## Comment

comment use `commentstring`, so you can check the `commentstring` of your file.

```lua
vim.keymap.set('n','ComComment',{noremap = true,silent = true})
vim.keymap.set('x','ComComment',{noremap = true,silent = true})
```

## Annotation

```lua
vim.keymap.set('n','ComAnnotation',{noremap = true,silent = true})
```

## Show

![image](https://user-images.githubusercontent.com/41671631/181735098-7e81fc60-3e14-4bfb-9322-a9bcab2edc80.gif)

## Liencese MIT