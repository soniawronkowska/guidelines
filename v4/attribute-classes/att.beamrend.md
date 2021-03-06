---
layout: sidebar
sidebar: s1
version: "v4"
title: "att.beamRend"
---
<div class="classSpec att">
   <h3 id="att.beamRend">att.beamRend</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">Attributes that record the visual rendition of beams.</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Module</strong></td>
         <td class="wovenodd-col2">MEI.cmn</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Members</strong></td>
         <td class="wovenodd-col2">
            <div class="parent">
               <div><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/beam.html">beam</a><span> (via <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.beam.vis.html">att.beam.vis</a>)</span></div>
               <div><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/beamspan.html">beamSpan</a><span> (via <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.beamspan.vis.html">att.beamSpan.vis</a>)</span></div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Attributes</strong></td>
         <td class="wovenodd-col2">
            <div class="attributeDef"><span class="attribute"><strong>@form</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Captures whether a beam is "feathered" and in which direction.</span>
               Allowed values are:
               "<span style="font-weight: 500;">acc</span>" <i>((accelerando) indicates that the secondary beams get progressively closer together
                  toward the end of the beam.)</i>,  "<span style="font-weight: 500;">mixed</span>" <i>((mixed acc and rit) for beams that are "feathered" in both directions.)</i>,  "<span style="font-weight: 500;">rit</span>" <i>((ritardando) means that the secondary beams become progressively more distant
                  toward the end of the beam.)</i>,  "<span style="font-weight: 500;">norm</span>" <i>((normal) indicates that the secondary beams are equidistant along the course of
                  the beam.)</i><span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.beamrend.html">att.beamRend</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@place</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Records the placement of the beam relative to the events it affects.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.beamplace.html">data.BEAMPLACE</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.beamrend.html">att.beamRend</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@slash</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Indicates presence of slash through the beam.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.boolean.html">data.BOOLEAN</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.beamrend.html">att.beamRend</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@slope</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Records the slope of the beam.</span>
               Value is a decimal number.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.beamrend.html">att.beamRend</a></span></div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Declaration</strong></td>
         <td class="wovenodd-col2">
            <div class="code" xml:space="preserve" data-lang="ODD"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;attDef <span class="attribute">ident=</span><span class="attributevalue">"form"</span> <span class="attribute">usage=</span><span class="attributevalue">"opt"</span>&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Captures whether a beam is "feathered" and in which direction.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;valList <span class="attribute">type=</span><span class="attributevalue">"closed"</span>&gt;</span>
                        
                        <div class="indent3 indent"><span data-indentation="3" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"acc"</span>&gt;</span>
                           
                           <div class="indent4 indent"><span data-indentation="4" class="element">&lt;desc&gt;</span>(accelerando) indicates that the secondary beams get progressively closer together
                              toward the end of the beam.<span data-indentation="4" class="element">&lt;/desc&gt;</span></div>
                           <span data-indentation="3" class="element">&lt;/valItem&gt;</span></div>
                        
                        <div class="indent3 indent"><span data-indentation="3" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"mixed"</span>&gt;</span>
                           
                           <div class="indent4 indent"><span data-indentation="4" class="element">&lt;desc&gt;</span>(mixed acc and rit) for beams that are "feathered" in both directions.<span data-indentation="4" class="element">&lt;/desc&gt;</span></div>
                           <span data-indentation="3" class="element">&lt;/valItem&gt;</span></div>
                        
                        <div class="indent3 indent"><span data-indentation="3" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"rit"</span>&gt;</span>
                           
                           <div class="indent4 indent"><span data-indentation="4" class="element">&lt;desc&gt;</span>(ritardando) means that the secondary beams become progressively more distant
                              toward the end of the beam.<span data-indentation="4" class="element">&lt;/desc&gt;</span></div>
                           <span data-indentation="3" class="element">&lt;/valItem&gt;</span></div>
                        
                        <div class="indent3 indent"><span data-indentation="3" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"norm"</span>&gt;</span>
                           
                           <div class="indent4 indent"><span data-indentation="4" class="element">&lt;desc&gt;</span>(normal) indicates that the secondary beams are equidistant along the course of
                              the beam.<span data-indentation="4" class="element">&lt;/desc&gt;</span></div>
                           <span data-indentation="3" class="element">&lt;/valItem&gt;</span></div>
                        <span data-indentation="2" class="element">&lt;/valList&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/attDef&gt;</span></div></code></div>
            <div class="code" xml:space="preserve" data-lang="ODD"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;attDef <span class="attribute">ident=</span><span class="attributevalue">"place"</span> <span class="attribute">usage=</span><span class="attributevalue">"opt"</span>&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Records the placement of the beam relative to the events it affects.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;datatype&gt;</span>
                        
                        <div class="indent3 indent"><span data-indentation="3" class="element">&lt;rng:ref
                              
                              <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.beamplace.html">data.BEAMPLACE</a>"</span></span>
                              /&gt;</span></div>
                        <span data-indentation="2" class="element">&lt;/datatype&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;constraintSpec <span class="attribute">ident=</span><span class="attributevalue">"check_beam_place"</span> <span class="attribute">scheme=</span><span class="attributevalue">"isoschematron"</span>&gt;</span>
                        
                        <div class="indent3 indent"><span data-indentation="3" class="element">&lt;constraint&gt;</span>
                           
                           <div class="indent4 indent"><span data-indentation="4" class="element">&lt;sch:rule <span class="attribute">context=</span><span class="attributevalue">"mei:beam[@place eq 'mixed' and not(descendant::mei:*[local-name() eq 'note' or local-name()
                                    eq 'chord'][@staff != ./@staff] or descendant::mei:*[local-name() eq 'note' or local-name()
                                    eq 'chord'][@staff != ancestor::mei:staff/@n])]"</span>&gt;</span>
                              
                              <div class="indent5 indent"><span data-indentation="5" class="element">&lt;sch:assert <span class="attribute">test=</span><span class="attributevalue">"count(descendant::mei:*[local-name() eq 'note' or local-name() eq 'chord'][@stem.dir])
                                       = count(descendant::mei:*[local-name() eq 'note' or local-name() eq 'chord'])"</span>&gt;</span>Stem direction must be specified for all notes and chords under the
                                 beam.<span data-indentation="5" class="element">&lt;/sch:assert&gt;</span></div>
                              
                              <div class="indent5 indent"><span data-indentation="5" class="element">&lt;sch:assert <span class="attribute">test=</span><span class="attributevalue">"count(distinct-values(descendant::mei:*[local-name() eq 'note' or local-name() eq
                                       'chord']/@stem.dir)) &gt; 1"</span>&gt;</span>Opposing stem directions are required for a beam with @place="mixed".<span data-indentation="5" class="element">&lt;/sch:assert&gt;</span></div>
                              <span data-indentation="4" class="element">&lt;/sch:rule&gt;</span></div>
                           
                           <div class="indent4 indent"><span data-indentation="4" class="element">&lt;sch:rule <span class="attribute">context=</span><span class="attributevalue">"mei:beam[@place eq 'mixed' and (descendant::mei:*[local-name() eq 'note' or local-name()
                                    eq 'chord'][@staff != ./@staff] or descendant::mei:*[local-name() eq 'note' or local-name()
                                    eq 'chord'][@staff != ancestor::mei:staff/@n])                 and count(descendant::mei:*[local-name()
                                    eq 'note' or local-name() eq 'chord'][@stem.dir]) = count(descendant::mei:*[local-name()
                                    eq 'note' or local-name() eq 'chord'])]"</span>&gt;</span>
                              
                              <div class="indent5 indent"><span data-indentation="5" class="element">&lt;sch:assert <span class="attribute">test=</span><span class="attributevalue">"count(distinct-values(descendant::mei:*[local-name() eq 'note' or local-name() eq
                                       'chord']/@stem.dir)) &gt; 1"</span>&gt;</span>Opposing stem directions are required for a beam with @place="mixed".<span data-indentation="5" class="element">&lt;/sch:assert&gt;</span></div>
                              <span data-indentation="4" class="element">&lt;/sch:rule&gt;</span></div>
                           <span data-indentation="3" class="element">&lt;/constraint&gt;</span></div>
                        <span data-indentation="2" class="element">&lt;/constraintSpec&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/attDef&gt;</span></div></code></div>
            <div class="code" xml:space="preserve" data-lang="ODD"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;attDef <span class="attribute">ident=</span><span class="attributevalue">"slash"</span> <span class="attribute">usage=</span><span class="attributevalue">"opt"</span>&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Indicates presence of slash through the beam.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;datatype&gt;</span>
                        
                        <div class="indent3 indent"><span data-indentation="3" class="element">&lt;rng:ref
                              
                              <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.boolean.html">data.BOOLEAN</a>"</span></span>
                              /&gt;</span></div>
                        <span data-indentation="2" class="element">&lt;/datatype&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/attDef&gt;</span></div></code></div>
            <div class="code" xml:space="preserve" data-lang="ODD"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;attDef <span class="attribute">ident=</span><span class="attributevalue">"slope"</span> <span class="attribute">usage=</span><span class="attributevalue">"opt"</span>&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Records the slope of the beam.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;datatype&gt;</span>
                        
                        <div class="indent3 indent"><span data-indentation="3" class="element">&lt;rng:data <span class="attribute">type=</span><span class="attributevalue">"decimal"</span>/&gt;</span></div>
                        <span data-indentation="2" class="element">&lt;/datatype&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/attDef&gt;</span></div></code></div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Constraint</strong></td>
         <td class="wovenodd-col2">
            <div>
               <div class="schematronText">Stem direction must be specified for all notes and chords under the beam.</div>
               <div class="schematronText">Opposing stem directions are required for a beam with @place="mixed".</div>
               <div class="schematronText">Opposing stem directions are required for a beam with @place="mixed".</div>
            </div>
            <div class="code" xml:space="preserve" data-lang="Schematron"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;sch:rule <span class="attribute">context=</span><span class="attributevalue">"mei:beam[@place eq 'mixed' and not(descendant::mei:*[local-name() eq 'note' or local-name()
                           eq 'chord'][@staff != ./@staff] or descendant::mei:*[local-name() eq 'note' or local-name()
                           eq 'chord'][@staff != ancestor::mei:staff/@n])]"</span>&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;sch:assert <span class="attribute">test=</span><span class="attributevalue">"count(descendant::mei:*[local-name() eq 'note' or local-name() eq 'chord'][@stem.dir])
                              = count(descendant::mei:*[local-name() eq 'note' or local-name() eq 'chord'])"</span>&gt;</span>Stem direction must be specified for all notes and chords under the
                        beam.<span data-indentation="2" class="element">&lt;/sch:assert&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;sch:assert <span class="attribute">test=</span><span class="attributevalue">"count(distinct-values(descendant::mei:*[local-name() eq 'note' or local-name() eq
                              'chord']/@stem.dir)) &gt; 1"</span>&gt;</span>Opposing stem directions are required for a beam with @place="mixed".<span data-indentation="2" class="element">&lt;/sch:assert&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/sch:rule&gt;</span></div>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;sch:rule <span class="attribute">context=</span><span class="attributevalue">"mei:beam[@place eq 'mixed' and (descendant::mei:*[local-name() eq 'note' or local-name()
                           eq 'chord'][@staff != ./@staff] or descendant::mei:*[local-name() eq 'note' or local-name()
                           eq 'chord'][@staff != ancestor::mei:staff/@n])                 and count(descendant::mei:*[local-name()
                           eq 'note' or local-name() eq 'chord'][@stem.dir]) = count(descendant::mei:*[local-name()
                           eq 'note' or local-name() eq 'chord'])]"</span>&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;sch:assert <span class="attribute">test=</span><span class="attributevalue">"count(distinct-values(descendant::mei:*[local-name() eq 'note' or local-name() eq
                              'chord']/@stem.dir)) &gt; 1"</span>&gt;</span>Opposing stem directions are required for a beam with @place="mixed".<span data-indentation="2" class="element">&lt;/sch:assert&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/sch:rule&gt;</span></div></code></div>
         </td>
      </tr>
   </table>
</div>