Editorial comment from @cybik
-----------------------------

Full disclosure, I started this list because I grew tired of throwing queries at Google to find nVidia-powered, GSync-enabled laptops to consider for acqusition.

I'm a Linux user first and foremost, and Optimus being fundamentally broken for Linux systems yet a staple of more affordable nVidia-powered laptops, I am somewhat limited in my pool of potential machines to choose from. Fortunately and luckily, I stumbled on [@Brainiarc7's gist](https://gist.github.com/Brainiarc7/c3fa09bc2ecb4153434cd98b6fb06238), which seems to indicate that GSync-enabled laptops actually have their screen wired to the nVidia GPU first, instead of the intel iGPU. This ultimately allows Linux to directly use the nVidia GPU properly instead of relying on unfortunately very interesting hacks like VGA Switcheroo (https://01.org/linuxgraphics/gfx-docs/drm/gpu/vga-switcheroo.html), which also have the side-effect (I'm told) of utterly borking Vulkan, another issue I can't allow since I need Vk support.
