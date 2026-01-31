+++
date = '2025-01-16T14:36:41-05:00'
draft = false
#title = ''
+++


<h1 style="font-size:40px;">
  C-Blinker <br>
  <a href="https://github.com/LimeyShark/C-Blinker" style="font-size: 25px;">
  My own C linker
  </a>
</h1>

<p style="font-size:30px; " width= "10">
<ul>
<li>A rudimentary C linker from scratch, coded in C </li>
<li>Capable of linking together an arbitrary number of object files into a runnable executable</li>
<li>mmap's input object files and checks that they're valid ELF object files, then reads ELF header to navigate ELF file and concatenates the .text sections and symbol tables, performing symbol resolution and relocation</li>
</ul>
</p>
<br>

<h1 style="font-size:40px;">
  Balloc <br>
  <a href="https://github.com/LimeyShark/Balloc" style="font-size: 25px;">
    My own memory allocator
  </a>
</h1>

<p style="font-size:30px; " width= "10">
<ul>
<li>A rudimentary implementation of Malloc from scratch, coded in C</li>
<li>Segregated explicit free list uses a prologue block as a sentinel node to keep track of 8 lists of differently sized of free blocks </li>
<li>Boundary tag coalescing ensures freed blocks are properly maintained and added to their respective free lists</li>
</ul>
</p>
<br>


<h1 style="font-size:40px;">
  BeaChat <br>
  <a href="https://github.com/LimeyShark/Beachat" style="font-size: 25px;">
  My own chat server 
  </a>
</h1>

<p style="font-size:30px; " width= "10">
<ul>
<li>A simple chat server that can accept multiple clients in multiple chats, coded in C from a provided skeleton</li>
<li>Programmed using Socket API, creates a server socket and accepts a client connection, capable of moving a client between chat rooms by transporting open socket descriptions via named domain sockets</li>
<li>Maintains a registry file of chat servers that maps each server’s port number to its current number of connected clients, with synchronization to ensure the target server has a vacancy before transporting</li>
</ul>
</p>
<br>


<h1 style="font-size:40px;">
  BDB <br>
  <a href="https://github.com/LimeyShark/BDB" style="font-size: 25px;">
  My own debugger
  </a>
</h1>

<p style="font-size:30px; " width= "10">
<ul>
<li>A rudimentary implementation of the GNU debugger ldb from scratch, coded in C</li>
</ul>
</p>
<br>



<h1 style="font-size:40px;">
  greB <br>
  <a href="https://github.com/LimeyShark/greb" style="font-size: 25px;">
  My own implementation of grep 
  </a>
</h1>


<p style="font-size:30px; " width= "10">
<ul>
<li>A rudimentary implementation of the grep command in linux from scratch, coded in C</li>
</ul>
</p>
<br>


