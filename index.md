---
layout: default
---
###### newbie pwner >.>

# CTF Writeups

> Not ready currently...


# Others

Learning by reading other's writeups and practising with my own words. This is where I take someone's writeup and study it. 


#### Heap Related
###### Glibc 2.35
*  [getting leaks via UAF to perform house of botcake attack into FSOP on stdout to leak a stack addr then ROP to fgets() stackframe](../../../../../tokyoking/ctf/tree/main/heap/otherbins/ImaginaryCTF23/mailman/README.md)
  
###### Glibc 2.31
*   [fake chunk into overwriting got entries to get a leak](../../../../../tokyoking/ctf/tree/main/heap/tcache/BACKDOOR23/Konsolidator)
*   [fastbin dup attack into free_hook overwrite](../../../../../tokyoking/ctf/tree/main/heap/otherbins/JUSTCTF22/pwn_notes/)   
    
###### Glibc 2.29
*   [house of force attack into overwriting malloc hook](../../../../../tokyoking/ctf/tree/main/heap/otherbins/SUNSHINECTF23/House_of_Sus)

#### Format String Exploits
*   [write ROP to saved rip of main](../../../../../tokyoking/ctf/tree/main/format_string/BACKDOOR23/Baby_formatter)
*   [overwrite the key to pass a check](../../../../../tokyoking/ctf/tree/main/format_string/BlueHensCTF24/)
*   
#### Shellcoding
*   [calling mprotect() into self modifying shellcode](../../../../../tokyoking/ctf/tree/main/shellcode/HKCERTCTF24/shellcode_runner3/)
*   [getting a leak from not cleared fs_base register into calling one_gaget](../../../../../tokyoking/ctf/tree/main/shellcode/HKCERTCTF24/shellcode_runner3(revenge)/)
*   
#### Buffer overflow
*   [Brute-forcing a fork() process into leaking canary](../../../../../tokyoking/ctf/tree/main/buffer_overflow/UTCCTF24)




| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four


### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
