# My PDF Reader Electron

Note:
1. Add `"./"` to `(e,t,n)=>{e.exports=function(){return new Worker(n.p+"pdf.worker.js")}}` in `bundle.js` => `(e,t,n)=>{e.exports=function(){return new Worker("./"+n.p+"pdf.worker.js")}}` to fix file not found issue.