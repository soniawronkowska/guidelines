---
layout: sidebar
sidebar: s1
version: "v3"
title: "att.bTrem.vis"

---

<div class="classSpec att">
   <h3 id="att.bTrem.vis">att.bTrem.vis</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">
            <span class="label">att.bTrem.vis</span> Visual domain attributes.
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Module</span>
         </td>
         <td class="wovenodd-col2">MEI.cmn</td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Members</span>
         </td>
         <td class="wovenodd-col2">
            <div class="parent">
               <div>
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/bTrem">bTrem</a> (direct member of att.bTrem.vis)
               </div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Attributes</span>
         </td>
         <td class="wovenodd-col2">
            <div class="attributeDef">
               <span class="attribute">@num.place</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">States where the tuplet number will be placed in relation to the note heads.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.PLACE">data.PLACE</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.numberplacement">att.numberplacement</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@num.visible</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Determines if the tuplet number is visible.</span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.BOOLEAN">data.BOOLEAN</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.numberplacement">att.numberplacement</a>
               </span>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Declaration</span>
         </td>
         <td class="wovenodd-col2">
            <div xml:space="preserve" class="pre">
               <div class="indent1">
                  <span data-indentation="1" class="element">&lt;classes&gt;</span>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;memberOf 
                        <span class="attribute">key=</span>
                        <span class="attributevalue">"
                           <a class="link_odd" href="/att.numberplacement">att.numberplacement</a>"
                        </span>/&gt;
                     </span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/classes&gt;</span>
               </div>
            </div>
         </td>
      </tr>
   </table>
</div>