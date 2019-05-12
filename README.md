## Git Clone
`git clone` is a command that clones a remote repository into a new folder on your local computer.

When you are working with remotes, the command you will most likely use is `git clone`, to get started. 

**NOTE** Git clone only needs to be run once.

<div style='background-color: #e4f4ff; padding: 1rem; display: flex; margin-bottom: 1rem;'>
  <div style='display: inline-block; width: 10%;'>
    <svg aria-hidden="true" style='margin: 0 auto; display: inline-block;' focusable="false" data-prefix="fas" data-icon="info-circle" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" class="svg-inline--fa fa-info-circle fa-w-16 fa-7x"><path fill="#4e6c99" d="M256 8C119.043 8 8 119.083 8 256c0 136.997 111.043 248 248 248s248-111.003 248-248C504 119.083 392.957 8 256 8zm0 110c23.196 0 42 18.804 42 42s-18.804 42-42 42-42-18.804-42-42 18.804-42 42-42zm56 254c0 6.627-5.373 12-12 12h-88c-6.627 0-12-5.373-12-12v-24c0-6.627 5.373-12 12-12h12v-64h-12c-6.627 0-12-5.373-12-12v-24c0-6.627 5.373-12 12-12h64c6.627 0 12 5.373 12 12v100h12c6.627 0 12 5.373 12 12v24z" class=""></path></svg>
  </div>
  <div style='display: inline-block; width: 90%; padding: .5rem;'>
    <div style='font-weight: 700; margin-bottom: .5rem;'>The origin remote</div>
    When you clone a repository with the <code>git clone</code> command.  It automatically creates a remote connection with the short name <b>origin</b>.
  </div>
</div>

### Git Clone Usage
The syntax for `git clone` is

```sh
git clone [remote url]
```

The remote url that you use can be either SSH or HTTPS, both will work fine for the initial clone.

### Git Clone Example
Let's imagine that you want to clone a repository to get working with it it.
