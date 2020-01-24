## 1. Was macht dieses Element?
* Bilder unterstützen das Verständnis von Texten und lockern textlastige Seiten auf.

## 2. Wann soll das Element eingesetzt werden?
* Zur Unterstützung der textuellen Kommunikation können Bilder eingesetzt werden (visuelle Kommunikation).
* Grosse (content-wide) Bilder sollen sparsam eingesetzt werden.

## 3. Regeln 
* Die Aufbereitung von Bildern und Illustrationen ist durch die Vorgaben von KOM geregelt (siehe Links).
* Illustrationen und Infografiken als SVG einsetzen, bei Fotografien auf genügend grosse Auflösung für alle Screengrössen achten.
* Ausser dem roten SBB Panel dürfen Bilder keine Overlays enthalten.
* Es dürfen nur kontextrelevante Bilder verwendet werden (das Bild muss zum Inhalt passen).
* Kombinieren verschiedener Stile kann die UX positiv beeinflussen (Fotografie für Gegebenheiten, Illustrationen für Konzepte)
* Um die Wichtigkeit von Bildern zu unterstreichen (zu priorisieren), können verschiedene Bildgrössen helfen.
* Bilder haben optional einen Beschreibungstext (Caption).

## 4. Ausprägungen und Zustände 
Bei Bildern werden folgende Stile unterschieden:
* Fotografie.
* Illustration.
* Infografik.

### 4.1 Key Visual 
* Nur Fotografien (keine Illustrationen) verwenden.
* Keyvisuals haben keinen eigenen Informationsgehalt.
* Keyvisuals können statische Bilder oder Videos sein. Animated GIFs sind nicht möglich.
    * Bilder und Videos werden grundsätzlich gleich behandelt.
* Keyvisuals haben nie Bildunterschriften oder Copyright-Infos.
* Keyvisuals haben je Endgerät ein festes Format, der Bildausschnitt passt sich dem Viewport an.
* Keyvisuals können als [Mediaslider](https://digital.sbb.ch/de/website/components/mediaslider) umgesetzt werden.
* Kein Beschreibungstext erlaubt.

### Formate
<table>
   <colgroup>
      <col>
      <col>
      <col>
      <col>
      <col>
   </colgroup>
   <thead>
      <tr role="row">
         <th colspan="1" scope="col">
         </th>
        <th colspan="1" scope="col">
               <p>Aspect Ratio</p>
         </th>
         <th colspan="1" scope="col">
               <p>Non-Retina</p>
         </th>
         <th colspan="1" scope="col">
               <p>Retina</p>
         </th>
         <th colspan="1" scope="col">
					 <p>Retina-HD (iPhone 7)</p>
         </th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <th>Tablet</th>
         <td>48:25</td>
         <td>768x400</td>
         <td>1536x800</td>
         <td colspan="1"><br></td>
      </tr>
      <tr role="row">
         <th colspan="1"><strong>Desktop</strong></th>
         <td colspan="1">
            <p>83:30</p>
         </td>
         <td>
            <p>1328x480</p>
         </td>
         <td>
            <p>2656x960</p>
         </td>
         <td colspan="1" c><br></td>
      </tr>
      <tr role="row">
         <th colspan="1">4K</th>
         <td colspan="1">83:30</td>
         <td colspan="1">2656x960</td>
         <td colspan="1">2656x960</td>
         <td colspan="1"><br></td>
      </tr>
      <tr role="row">
         <th colspan="1">Mobile</th>
         <td colspan="1">166:133</td>
         <td colspan="1">320x266</td>
         <td colspan="1">640x532</td>
         <td colspan="1">960x798</td>
      </tr>
      <tr role="row">
         <th colspan="1">5K</th>
         <td colspan="1"><br></td>
         <td colspan="1"><br></td>
         <td colspan="1"><br></td>
         <td colspan="1"><br></td>
      </tr>
   </tbody>
</table>


## 4.2 Infobild 
* Infobilder können statische Bilder, animated GIFs oder Videos sein.
    * Statische Bilder, animated GIFs und Videos werden grundsätzlich gleich behandelt.
* Infobilder können optional eine Bildunterschrift und eine Copyright-Info unter dem Bild stehen haben.
    * Empfohlene Textlänge der Bildunterschrift inkl. Copyright-Info: sollte auf Desktop max. 2 Zeilen umfassen.
* Infobilder dürfen kein Panel verwenden.
* Infobilder sind nie verlinkt.
* Infobilder haben immer das Format 16:9.
* Infobilder haben keine Grossansicht.

## 4.3 Lazyload 
* Wenn viele Bilder auf einer Seite vorhanden sind, dann werden Bilder ausserhalb des Viewports lazyloaded.

## 4.4 Innerhalb eines Teasers
* Bild muss bei Mouseover leicht reingezoomt werden.

## 4.5 Als Hintergrund (z.B. Karte)
* Beim Scrollen nach unten, wird das Bild eingezoomt, beim Scrollen nach oben wird es ausgezoomt.
* Bild soll den ganzen Viewport des Contentbereichs bedecken.
* Text und Interaktionselemente (Buttons) über dem Bild sind erlaubt.
* Wichtig: Kontraste einhalten → Bilder sollten dunkle Farben beinhalten, sodass Text in weiss darüber geht.