````
<svg>
    <foreignObject>
        <iframe src='https://chromestatus.com/metrics/feature/timeline/popularity/1689' onload="document.body.children[0].innerHTML=`<h1>Web Components technologies<br>ChromeStatus usage stats</h1>`+'CustomElementsRegisteryDefine/1689,ElementAttachShadow/804,ElementAttachShadowOpen/907,ElementAttachShadowClosed/908,ElementCreateShadowRootMultipleWithUserAgentShadowRoot/800,HTMLSlotElement/1898,CSSSelectorPseudoSlotted/1118,SlotAssignNode/3442,SlotChangeEventAddEventlistener/1468,ShadowRootDelegatesFocus/1308,ShadowRootPointerLockElement/1422,ElementAttachInternals/3435,ElementCreateShadowRootMultiple/779,NodeGetRootNode/1467'.split(',').map(topic=>{let [title,id]=topic.split('/');return `<h2><span id='load${id}'>loading: </span><a href='https://chromestatus.com/metrics/feature/timeline/popularity/${id}'>${title}</a></h2><svg width='700' height='750'><foreignObject x='0' y='0' width='700' height='750'><iframe src='https://chromestatus.com/metrics/feature/timeline/popularity/${id}' scrolling='no' style='width:700px;height:750px' onload=document.querySelector('#load${id}').remove() ></iframe></foreignObject></svg>`}).join``"></iframe>
    </foreignObject>
</svg>
````
