# Nitro-Type-all-cars
Nitro Type all car in the game


go to the GARAGE and INSPECT element and go to CONSOLE

COPY AND PASTE IN CONSOLE
Code here -->  javascript:eval(`\x24.ajax('/api/cars').done(function(b){\x24('.car-picker \x3e div').empty(),\x24('.arrange-cars').remove(),b.data.forEach(function(c,e){\x24('.car-picker \x3e div').append(\x60\x3cdiv class="spot" data-id="\x24{e}"\x3e\x3cdiv class="car" data-id="\x24{c.carID}" data-angle=""\x3e\x3cdiv class="car-name"\x3e\x3cspan\x3e\x24{c.name}\x3cbr/\x3e\x24{c.purchasable?'':'{'} \x24\x24{c.price.addCommas()} \x24{c.purchasable?'':'}'}\x3c/span\x3e\x3c/div\x3e\x3cdiv class="image" style="background-image: url('/cars/\x24{c.carID}_small_1.png'); ')"\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x60)})}),function(b,c){var e=document;if(!e.getElementById(c)){var f=e.createElement('script');f.src=b,f.id=c,e.body.appendChild(f)}}('//cdn.jsdelivr.net/npm/fake-xmlhttprequest@1.2.0/lib/fake-xmlhttprequest.min.js','fake-xmlhttprequest'),setTimeout(function(){FakeXMLHttpRequest.setup(),FakeXMLHttpRequest.addHandler({url:new RegExp('/api/cars/(\\\\d+)/use'),status:200,statusText:'OK',response:'{"success":true,"data":[]}'}),FakeXMLHttpRequest.addHandler({url:'/api/achievements/check/',status:200,statusText:'OK',response:function(b,c){var e=decodeURI(c).match(new RegExp('ids\\\\[\\\\]=(\\\\d+)'))[1];return\x60{"success":true,"data":{"achieved":{"\x24{e}":1}}}\x60}})},3e3)`)
