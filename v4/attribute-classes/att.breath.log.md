---
layout: sidebar
sidebar: s1
version: "v4"
title: "att.breath.log"
---
<div class="classSpec att">
   <h3 id="att.breath.log">att.breath.log</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">Logical domain attributes.</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Module</strong></td>
         <td class="wovenodd-col2">MEI.cmn</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Members</strong></td>
         <td class="wovenodd-col2">
            <div class="parent">
               <div><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/breath.html">breath</a> (direct member of att.breath.log)
               </div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Attributes</strong></td>
         <td class="wovenodd-col2">
            <div class="attributeDef"><span class="attribute"><strong>@layer</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Identifies the layer to which a feature applies.</span>
               One or more values of datatype <span style="font-weight: 500;">positiveInteger</span>, separated by spaces.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.layerident.html">att.layerIdent</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@part</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Indicates the part in which the current feature should appear. Use '%all' when the
                  feature should occur in every part.</span>
               One or more values of datatype <span style="font-weight: 500;">
                  a string matching the following regular expression: "(%all|#[\i][\c]+)"
                  </span>, separated by spaces.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.partident.html">att.partIdent</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@partstaff</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Signifies the part staff on which a notated feature occurs. Use '%all' when the
                  feature should occur on every staff.</span>
               One or more values of datatype <span style="font-weight: 500;">
                  a string matching the following regular expression: "(%all|\d+(-\d+)?)"
                  </span>, separated by spaces.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.partident.html">att.partIdent</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@staff</strong></span><span class="attributeUsage">(rec)</span><span class="attributeDesc">Signifies the staff on which a notated event occurs or to which a control event
                  applies. Mandatory when applicable.</span>
               One or more values of datatype <span style="font-weight: 500;">positiveInteger</span>, separated by spaces.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.staffident.html">att.staffIdent</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@startid</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Holds a reference to the first element in a sequence of events to which the feature
                  applies.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.startid.html">att.startId</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@tstamp</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Encodes the onset time in terms of musical time, i.e., beats[.fractional beat part],
                  as expressed in the written time signature.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.beat.html">data.BEAT</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.timestamp.logical.html">att.timestamp.logical</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@when</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Indicates the point of occurrence of this feature along a time line. Its value must
                  be
                  the ID of a <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/when.html">when</a> element elsewhere in the document.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.alignment.html">att.alignment</a></span></div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Declaration</strong></td>
         <td class="wovenodd-col2">
            <div class="code" xml:space="preserve" data-lang="ODD"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classes&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.alignment.html">att.alignment</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.layerident.html">att.layerIdent</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.partident.html">att.partIdent</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.staffident.html">att.staffIdent</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.startid.html">att.startId</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.timestamp.logical.html">att.timestamp.logical</a>"</span></span>/&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/classes&gt;</span></div></code></div>
         </td>
      </tr>
   </table>
</div>