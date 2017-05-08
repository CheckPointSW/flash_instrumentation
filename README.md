# Debug Instrumentation via Flash ActionScript
## By Omer Gull @ Check Point Software Technologies

Browser plug-ins have always been an attractive target for attackers to exploit. In the last couple of years, the most prevalent attack platform was undoubtedly – Flash. With 250+ CVEs in 2016 alone, and incorporation in practically every exploit kit, Flash exploits are everywhere and deserve our attention.

As researchers, we stumble upon many cases where we are required to analyze exploits found in the wild and collect as much information as possible regarding the exploit`s internal workings. This process quite often proves to be tedious and very time consuming, making the research task far from optimal. As most of an exploit’s juicy parts (such as ROP chains, Shellcodes and payload) are generated at runtime, we decided to take a different approach and make this process much more informative by utilizing the existing abilities found in native level debuggers.
Using this approach, we were able to gain a much wider view into the inner working of Flash-based exploits, making the research process much quicker and easier to manage.

This report explains the details of our approach and its advantages as well as showing some popular use cases in which it can be applied. But before diving in to Flash exploration techniques, let’s quickly go over the SWF basics.

http://blog.checkpoint.com/2017/05/05/debug-instrumentation-via-flash-actionscript/
