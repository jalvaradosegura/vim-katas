# Copy words and more

Change this text:

```text
No no no no no no yes no

yes yes yes yes
yes yes yes
yes yes
yes

(copy the content inside the parentheses below)
"copy the content inside the double quotes below"
'copy the content inside the quotes below'
```

to this:

```text
No no no no no no yes no
yes

yes yes yes yes
yes yes yes
yes yes
yes
yes yes yes yes
yes yes yes
yes yes
yes

(copy the content inside the parentheses below)
copy the content inside the parentheses below
"copy the content inside the double quotes below"
copy the content inside the double quotes below
'copy the content inside the quotes below'
copy the content inside the quotes below
```

Place yourself anywhere at the first line.

Navigate to the first word `yes` using `w` or `e` or `l`.

Once you are anywhere within the word `yes` press `yiw` (this will copy the inner content of the current word). Then press `escape`', the'n `o`, then `cmd+v` (macOS) or `ctrl+v` (windows)
 
Place yourself anywhere within the big paragraph of yes.

Press `yip` (this will copy the inner content of the current paragraph).

Go to the last line of the paragraph and press `p`

Go to the line with parentheses, place yourself anywhere within the parentheses and press `yi(`, then copy below with `o`, then `cmd+v` (macOS) or `ctrl+v` (windows)

Go to the line with double quotes, place yourself anywhere within the double quotes and press `yi"`, then copy below with `o`, then `cmd+v` (macOS) or `ctrl+v` (windows)

Go to the line with single quotes, place yourself anywhere within the single quotes and press `yi'`, then copy below with `o`, then `cmd+v` (macOS) or `ctrl+v` (windows)

*Note*: notice the similarity between the main commands `yiw`, `yip`, `yi(`, `yi"`, `yi'`.It only depends on what we want to copy, but there is a structure.
With this you can start detecting the inner language of vim and how you can infer some things
