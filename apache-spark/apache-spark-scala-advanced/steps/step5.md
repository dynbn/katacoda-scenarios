**Step 2:** Let us now create a function which takes parameters and has a return type.

`:paste`

**Note:** After pasting following code in the scala terminal, Press  `Ctrl` + `D` to run code.

```def married(name: String, times: Int): String = {
return name + " has married " + times + " times"
}```

Now, exit out of the paste mode and simply call this function by its name.

`married("Ross", 3)`


Please note that the return type (which is String, in this case) and also the keyword return are optional. Scala can determine the return type based on the last expression in the function body as shown below.

 