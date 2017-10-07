---
layout: sidebar
sidebar: s1
version: "v3"
title: "att.visualoffset2.vo"

---

<div class="classSpec att">
   <h3 id="att.visualoffset2.vo">att.visualoffset2.vo</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">
            <span class="label">att.visualoffset2.vo</span> Vertical offset attributes requiring a pair of attributes.
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Module</span>
         </td>
         <td class="wovenodd-col2">MEI.shared</td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Members</span>
         </td>
         <td class="wovenodd-col2">
            <div class="parent">
               <div>
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/curve">curve</a>
                  <span> (via 
                     <a class="link_odd_classSpec" href="/{{ page.version }}/att.visualoffset2">att.visualoffset2</a>)
                  </span>
               </div>
               <div>
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/bend">bend</a>
                  <span> (via 
                     <a class="link_odd_classSpec" href="/{{ page.version }}/att.bend.vis">att.bend.vis</a>)
                  </span>
               </div>
               <div>
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/gliss">gliss</a>
                  <span> (via 
                     <a class="link_odd_classSpec" href="/{{ page.version }}/att.gliss.vis">att.gliss.vis</a>)
                  </span>
               </div>
               <div>
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/hairpin">hairpin</a>
                  <span> (via 
                     <a class="link_odd_classSpec" href="/{{ page.version }}/att.hairpin.vis">att.hairpin.vis</a>)
                  </span>
               </div>
               <div>
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/line">line</a>
                  <span> (via 
                     <a class="link_odd_classSpec" href="/{{ page.version }}/att.line.vis">att.line.vis</a>)
                  </span>
               </div>
               <div>
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/phrase">phrase</a>
                  <span> (via 
                     <a class="link_odd_classSpec" href="/{{ page.version }}/att.phrase.vis">att.phrase.vis</a>)
                  </span>
               </div>
               <div>
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/slur">slur</a>
                  <span> (via 
                     <a class="link_odd_classSpec" href="/{{ page.version }}/att.slur.vis">att.slur.vis</a>)
                  </span>
               </div>
               <div>
                  <a class="link_odd_elementSpec" href="/{{ page.version }}/tie">tie</a>
                  <span> (via 
                     <a class="link_odd_classSpec" href="/{{ page.version }}/att.tie.vis">att.tie.vis</a>)
                  </span>
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
               <span class="attribute">@endvo</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records a vertical adjustment of a feature's programmatically-determined end
                  point.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.MEASUREMENTREL">data.MEASUREMENTREL</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.visualoffset2.vo">att.visualoffset2.vo</a>
               </span>
            </div>
            <div class="attributeDef">
               <span class="attribute">@startvo</span>
               <span class="attributeUsage">(optional)</span>
               <span class="attributeDesc">Records a vertical adjustment of a feature's programmatically-determined start
                  point.
               </span>
               Value conforms to 
               <a class="link_odd_classSpec" href="/{{ page.version }}/data.MEASUREMENTREL">data.MEASUREMENTREL</a>.
               
               <span class="attributeClasses">
                  <a class="link_odd" href="/{{ page.version }}/att.visualoffset2.vo">att.visualoffset2.vo</a>
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
                  <span data-indentation="1" class="element">&lt;attDef 
                     <span class="attribute">ident=</span>
                     <span class="attributevalue">"startvo"</span> 
                     <span class="attribute">usage=</span>
                     <span class="attributevalue">"opt"</span>&gt;
                  </span>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;desc&gt;</span>Records a vertical adjustment of a feature's programmatically-determined start
                     point.
                     <span data-indentation="2" class="element">&lt;/desc&gt;</span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;datatype 
                        <span class="attribute">maxOccurs=</span>
                        <span class="attributevalue">"1"</span> 
                        <span class="attribute">minOccurs=</span>
                        <span class="attributevalue">"1"</span>&gt;
                     </span>
                     
                     <div class="indent3">
                        <span data-indentation="3" class="element">&lt;rng:ref 
                           <span class="attribute">name=</span>
                           <span class="attributevalue">"
                              <a class="link_odd" href="/data.MEASUREMENTREL">data.MEASUREMENTREL</a>"
                           </span>/&gt;
                        </span>
                     </div>
                     
                     <span data-indentation="2" class="element">&lt;/datatype&gt;</span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/attDef&gt;</span>
               </div>
            </div>
            <div xml:space="preserve" class="pre">
               <div class="indent1">
                  <span data-indentation="1" class="element">&lt;attDef 
                     <span class="attribute">ident=</span>
                     <span class="attributevalue">"endvo"</span> 
                     <span class="attribute">usage=</span>
                     <span class="attributevalue">"opt"</span>&gt;
                  </span>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;desc&gt;</span>Records a vertical adjustment of a feature's programmatically-determined end
                     point.
                     <span data-indentation="2" class="element">&lt;/desc&gt;</span>
                  </div>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;datatype 
                        <span class="attribute">maxOccurs=</span>
                        <span class="attributevalue">"1"</span> 
                        <span class="attribute">minOccurs=</span>
                        <span class="attributevalue">"1"</span>&gt;
                     </span>
                     
                     <div class="indent3">
                        <span data-indentation="3" class="element">&lt;rng:ref 
                           <span class="attribute">name=</span>
                           <span class="attributevalue">"
                              <a class="link_odd" href="/data.MEASUREMENTREL">data.MEASUREMENTREL</a>"
                           </span>/&gt;
                        </span>
                     </div>
                     
                     <span data-indentation="2" class="element">&lt;/datatype&gt;</span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/attDef&gt;</span>
               </div>
            </div>
         </td>
      </tr>
   </table>
</div>