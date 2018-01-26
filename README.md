# UPD-PunchHole
Creating direct P2P UDP Connection between Machines behind NAT.

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="781px" version="1.1" content="&lt;mxfile userAgent=&quot;Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/63.0.3239.132 Safari/537.36&quot; version=&quot;8.0.2&quot; editor=&quot;www.draw.io&quot; type=&quot;google&quot;&gt;&lt;diagram id=&quot;69948b7f-9af0-f3e7-b139-8c415ea9c7a9&quot; name=&quot;Page-1&quot;&gt;5VpRc+MmEP41ns7cTDISSLbz6Nhp05nL1VP72rtHLGGLiSw0Eo6d/voCAkkgOeckspxr85DAChb49mNZlgzgdHv4LUNp9EBDHA+AEx4GcDYAwHU8wP8IyXMh8R2/EGwyEqpGlWBB/sG6p5LuSIhzoyGjNGYkNYUBTRIcMEOGsozuzWZrGpujpmiDG4JFgOKm9G8SsqiQjn2nkt9json0yK6jvqxQ8LjJ6C5R4w0AXMuf4vMWaV2qfR6hkO5rIng3gNOMUlaUtocpjgW2Grai369HvpbzznDCTukAsTtyx+Bm7Afe2HVurpSGJxTvFBbTmAhlwJmoKbNnDZNcKBaqnAG83UeE4UWKAvF1z4nBZRHbxrzm8qJSjDOGD0dn65YYcG5husUse+ZNVAdPoaZYBUaqvq9s5Gpko5p9hkqGFC02peYKGl5Q6JyIFDiO1O3FkRqOPxJUsAHVXRBRLlngjC/zBbTcXtCCwERr2ALWsAWsctt3ipbXQKsBEHcbqSiuY3yYCH/HccBJqIqzIEZ5TgITpzWJ4ymNaSZVaLck+vEJf1PMlJXvonI98kX9QNg3s/pdNS0mhcOGJ7VQ5xOnuyzALzschrINZi/xp2m9mnn8FutoWYZjxMiTOc02i6kR5pTIXXywLG9vJa2iWJ7qVfe1lqLydNOKgKWowKChSBKoXPbbODXsmVMlbcCZaAMuSQkITUt6th84lRJ8LYYi1+uPEqMGJe55D+GVH3CeiwDJZgh3sMy0f84y+og1AxKaYIsUSoRiskkEibiNub+Ht8JdEx5vTdSHLQlDMUyrszcPz4wybjsqel1Bv5sDwN6a7s2oeQI4LYSC5zgAbn5+y0CnG8P48CMZxm260Ukg/QhwiuAv56XPJGcf30JXNx2ZqDwPlYlgW/TUFmrax183Jmq6tZ/XRF25N9e3dpF3URONOwxGcn5Csk7j3nrY69aDl+vKGr1EvRcNcTzgm7ta118d4oxMRWBkKTpjiOM2T9KF4AsXzcGc//46E7+nRRZJbLqP6RO6cAE3JyQE2u64Z3EBWqnhAoaxhJqvY7gRpcI49zQWvnu+S4JIt+HjVc20MNWCZURyGSuxiIZiFqK2y7EoMxFFBRlGTChNdxkuWVAwos4FZ4XZHuNE93tAQUQSnMsvvCQUfpksr2vTSqtZdcaknFODJBsu8KvakqbihADH0kmUs2UdS68YcaLxRZyBVFbaxHeanCoDMSNvch5SNXOXTVItGBY55MmLVArJkxa53LrOMjLDh5wfRb+IAgoeE7qP5XEAnK2Ozgu64CLHlcscV50kNfUtI2rRKrMlP+wKqsnqzJqTIxn7MCkN5BLE1IdoK2iSrPJU6nI4PXGWIIHw72IjIEnv+R9/LgXmYg+EiKEVyrmeaaFQCAlTeOTWIGU1lrGWQ9dCqbRgUALJIiS+IbkNVTIfh71gBW3DihkgsSRuUTHfVK5vRjLxwGAeGEHdSewJ5zpvz1ebVSzpZQ3v6PrpU7l8KxerUBA2bZpU+lK6T2qEkRuhQZkaRQoNdaWSNHKPoETjNlPsOgrc/8CfulbWfgibDtX3Wg/pszhU0HCos8lycjtZ3LUwasFohiUZSkd5kiF1qB88x/xIlaHSDzL+qwL3z6szPgF4/onxUWmzbqFvPpm8/Y70qoStayRsrx1dneOM8HUJ+1Q3pnqOV9+gKoO8P8kLTrgmXfRxAFpPkh4Yv+2aBK34HI4sRee8JrVF472QzXhUck1WjQ1WaSaKuk3FjtgGTyAbuOilHFpPUSVpXsu2MlIvadvfuwO42Pum5aicOhUNpwc6zPScwqojR1NP75vWyVcmC19LKtdKBDdex89Jqr4fOCtSjY6Syr0oqS7qqca2g3njsWi//wAI++PUf+gpQb7HrWOS3qtvovyXKofyjls0xCivovT3Pd1ZoZHbcpnp79EBNFPBX/B+UF3+P7oFO3uv86wtBVtuOuNuzMKr1b8yFluy+n9RePcv&lt;/diagram&gt;&lt;/mxfile&gt;" onclick="(function(svg){var src=window.event.target||window.event.srcElement;while (src!=null&amp;&amp;src.nodeName.toLowerCase()!='a'){src=src.parentNode;}if(src==null){if(svg.wnd!=null&amp;&amp;!svg.wnd.closed){svg.wnd.focus();}else{var r=function(evt){if(evt.data=='ready'&amp;&amp;evt.source==svg.wnd){svg.wnd.postMessage(decodeURIComponent(svg.getAttribute('content')),'*');window.removeEventListener('message',r);}};window.addEventListener('message',r);svg.wnd=window.open('https://www.draw.io/?client=1&amp;lightbox=1&amp;edit=_blank');}}})(this);" viewBox="0 0 781 771" style="cursor:pointer;max-width:100%;max-height:771px;"><defs/><g transform="translate(0.5,0.5)"><rect x="20" y="210" width="120" height="60" fill="#ffffff" stroke="#000000" pointer-events="none"/><g transform="translate(58.5,233.5)"><switch><foreignObject style="overflow:visible;" pointer-events="all" width="42" height="12" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; vertical-align: top; width: 43px; white-space: nowrap; word-wrap: normal; text-align: center;"><div xmlns="http://www.w3.org/1999/xhtml" style="display:inline-block;text-align:inherit;text-decoration:inherit;">Client A</div></div></foreignObject><text x="21" y="12" fill="#000000" text-anchor="middle" font-size="12px" font-family="Helvetica">Client A</text></switch></g><rect x="660" y="210" width="120" height="60" fill="#ffffff" stroke="#000000" pointer-events="none"/><g transform="translate(698.5,233.5)"><switch><foreignObject style="overflow:visible;" pointer-events="all" width="42" height="12" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; vertical-align: top; width: 43px; white-space: nowrap; word-wrap: normal; text-align: center;"><div xmlns="http://www.w3.org/1999/xhtml" style="display:inline-block;text-align:inherit;text-decoration:inherit;">Client B</div></div></foreignObject><text x="21" y="12" fill="#000000" text-anchor="middle" font-size="12px" font-family="Helvetica">Client B</text></switch></g><rect x="300" y="0" width="160" height="100" rx="15" ry="15" fill="#ffffff" stroke="#000000" pointer-events="none"/><g transform="translate(346.5,43.5)"><switch><foreignObject style="overflow:visible;" pointer-events="all" width="66" height="12" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; vertical-align: top; width: 67px; white-space: nowrap; word-wrap: normal; text-align: center;"><div xmlns="http://www.w3.org/1999/xhtml" style="display:inline-block;text-align:inherit;text-decoration:inherit;">Echo Server</div></div></foreignObject><text x="33" y="12" fill="#000000" text-anchor="middle" font-size="12px" font-family="Helvetica">Echo Server</text></switch></g><path d="M 113.3 213.79 L 107.51 205.63 L 281.21 82.22 L 275.13 73.66 L 299.59 75.29 L 293.08 98.93 L 287 90.37 Z" fill="#ffffff" stroke="#000000" stroke-linejoin="round" stroke-miterlimit="10" pointer-events="none"/><path d="M 692.03 205.4 L 687.1 214.1 L 475.49 93.98 L 470.31 103.11 L 461.43 80.25 L 485.61 76.15 L 480.43 85.28 Z" fill="#ffffff" stroke="#000000" stroke-linejoin="round" stroke-miterlimit="10" pointer-events="none"/><g transform="translate(199.5,145.5)rotate(-35,40,6)"><switch><foreignObject style="overflow:visible;" pointer-events="all" width="80" height="12" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; vertical-align: top; width: 80px; white-space: nowrap; word-wrap: normal; text-align: center;"><div xmlns="http://www.w3.org/1999/xhtml" style="display:inline-block;text-align:inherit;text-decoration:inherit;">Hello Message</div></div></foreignObject><text x="40" y="12" fill="#000000" text-anchor="middle" font-size="12px" font-family="Helvetica">Hello Message</text></switch></g><g transform="translate(519.5,145.5)rotate(30,40,6)"><switch><foreignObject style="overflow:visible;" pointer-events="all" width="80" height="12" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; vertical-align: top; width: 80px; white-space: nowrap; word-wrap: normal; text-align: center;"><div xmlns="http://www.w3.org/1999/xhtml" style="display:inline-block;text-align:inherit;text-decoration:inherit;">Hello Message</div></div></foreignObject><text x="40" y="12" fill="#000000" text-anchor="middle" font-size="12px" font-family="Helvetica">Hello Message</text></switch></g><g transform="translate(262.5,303.5)rotate(-90,47.5,6)"><switch><foreignObject style="overflow:visible;" pointer-events="all" width="95" height="12" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; vertical-align: top; width: 95px; white-space: nowrap; word-wrap: normal; text-align: center;"><div xmlns="http://www.w3.org/1999/xhtml" style="display:inline-block;text-align:inherit;text-decoration:inherit;">Active Clients List</div></div></foreignObject><text x="48" y="12" fill="#000000" text-anchor="middle" font-size="12px" font-family="Helvetica">Active Clients List</text></switch></g><g transform="translate(142.5,83.5)rotate(-35,47.5,6)"><switch><foreignObject style="overflow:visible;" pointer-events="all" width="95" height="12" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; vertical-align: top; width: 95px; white-space: nowrap; word-wrap: normal; text-align: center;"><div xmlns="http://www.w3.org/1999/xhtml" style="display:inline-block;text-align:inherit;text-decoration:inherit;">Active Clients List</div></div></foreignObject><text x="48" y="12" fill="#000000" text-anchor="middle" font-size="12px" font-family="Helvetica">Active Clients List</text></switch></g><path d="M 159.5 245 L 159.5 255.5 L 140.5 240 L 159.5 224.5 L 159.5 235 L 640.5 235 L 640.5 224.5 L 659.5 240 L 640.5 255.5 L 640.5 245 Z" fill="#ffffff" stroke="#000000" stroke-linejoin="round" stroke-miterlimit="10" pointer-events="none"/><g transform="translate(177.5,213.5)"><switch><foreignObject style="overflow:visible;" pointer-events="all" width="144" height="12" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; vertical-align: top; width: 145px; white-space: nowrap; word-wrap: normal; text-align: center;"><div xmlns="http://www.w3.org/1999/xhtml" style="display:inline-block;text-align:inherit;text-decoration:inherit;">Start P2P UDP Connection</div></div></foreignObject><text x="72" y="12" fill="#000000" text-anchor="middle" font-size="12px" font-family="Helvetica">Start P2P UDP Connection</text></switch></g><g transform="translate(4.5,429.5)"><switch><foreignObject style="overflow:visible;" pointer-events="all" width="220" height="114" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; vertical-align: top; overflow: hidden; max-height: 130px; max-width: 220px; width: 220px; white-space: normal; word-wrap: normal;"><div xmlns="http://www.w3.org/1999/xhtml" style="display:inline-block;text-align:inherit;text-decoration:inherit;"><h1>UDP Hole Punch</h1><p>This Method is used to create pure UDP P2P Connection between to Machines behind NAT.</p></div></div></foreignObject><text x="110" y="63" fill="#000000" text-anchor="middle" font-size="12px" font-family="Helvetica">[Not supported by viewer]</text></switch></g><g transform="translate(164.5,559.5)"><switch><foreignObject style="overflow:visible;" pointer-events="all" width="530" height="203" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; vertical-align: top; overflow: hidden; max-height: 210px; max-width: 530px; width: 530px; white-space: normal; word-wrap: normal;"><div xmlns="http://www.w3.org/1999/xhtml" style="display:inline-block;text-align:inherit;text-decoration:inherit;"><h1>Steps:</h1><div>1. The Clients send's acknowledge message to echo server.</div><div><br /></div><div>2. The Server save the client's  external IP and PORT in database, then it sends the client the list of all clients that are connected.</div><div><br /></div><div>3. The Client can now open Direct P2P UDP connection with other Clients.</div><div><br /></div><div><br /></div><div>** The Echo Server can send the client is own external's IP and PORT, then he can send it to another Database.</div></div></div></foreignObject><text x="265" y="108" fill="#000000" text-anchor="middle" font-size="12px" font-family="Helvetica">[Not supported by viewer]</text></switch></g><path d="M 300 426 C 300 378 460 378 460 426 L 460 534 C 460 582 300 582 300 534 Z" fill="#ffffff" stroke="#000000" stroke-miterlimit="10" pointer-events="none"/><path d="M 300 426 C 300 462 460 462 460 426" fill="none" stroke="#000000" stroke-miterlimit="10" pointer-events="none"/><g transform="translate(341.5,486.5)"><switch><foreignObject style="overflow:visible;" pointer-events="all" width="77" height="27" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; vertical-align: top; width: 78px; white-space: nowrap; word-wrap: normal; text-align: center;"><div xmlns="http://www.w3.org/1999/xhtml" style="display:inline-block;text-align:inherit;text-decoration:inherit;">DATABASE<div>Store's Clients</div></div></div></foreignObject><text x="39" y="20" fill="#000000" text-anchor="middle" font-size="12px" font-family="Helvetica">[Not supported by viewer]</text></switch></g><path d="M 329.02 398.77 L 319.03 398.23 L 333.97 119.2 L 323.48 118.64 L 339.97 100.5 L 354.44 120.3 L 343.95 119.74 Z" fill="#ffffff" stroke="#000000" stroke-linejoin="round" stroke-miterlimit="10" pointer-events="none"/><path d="M 415.03 100.77 L 425.02 100.23 L 439.95 379.26 L 450.44 378.7 L 435.97 398.5 L 419.48 380.36 L 429.97 379.8 Z" fill="#ffffff" stroke="#000000" stroke-linejoin="round" stroke-miterlimit="10" pointer-events="none"/><path d="M 296.62 21.28 L 302.57 29.32 L 68.65 202.42 L 74.89 210.86 L 50.4 209.7 L 56.45 185.94 L 62.7 194.38 Z" fill="#ffffff" stroke="#000000" stroke-linejoin="round" stroke-miterlimit="10" pointer-events="none"/><path d="M 457.73 29.48 L 463.11 21.05 L 736.25 195.3 L 741.9 186.45 L 749.58 209.73 L 725.22 212.58 L 730.87 203.73 Z" fill="#ffffff" stroke="#000000" stroke-linejoin="round" stroke-miterlimit="10" pointer-events="none"/><g transform="translate(532.5,73.5)rotate(30,47.5,6)"><switch><foreignObject style="overflow:visible;" pointer-events="all" width="95" height="12" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; vertical-align: top; width: 95px; white-space: nowrap; word-wrap: normal; text-align: center;"><div xmlns="http://www.w3.org/1999/xhtml" style="display:inline-block;text-align:inherit;text-decoration:inherit;">Active Clients List</div></div></foreignObject><text x="48" y="12" fill="#000000" text-anchor="middle" font-size="12px" font-family="Helvetica">Active Clients List</text></switch></g><g transform="translate(420.5,293.5)rotate(-90,29,6)"><switch><foreignObject style="overflow:visible;" pointer-events="all" width="58" height="12" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; vertical-align: top; width: 59px; white-space: nowrap; word-wrap: normal; text-align: center;"><div xmlns="http://www.w3.org/1999/xhtml" style="display:inline-block;text-align:inherit;text-decoration:inherit;">New Client</div></div></foreignObject><text x="29" y="12" fill="#000000" text-anchor="middle" font-size="12px" font-family="Helvetica">New Client</text></switch></g></g></svg>
