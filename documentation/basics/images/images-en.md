## 1. What does the element do?
Images support the understanding of texts and loosen up text-heavy pages.

## 2. When should the element be used?
* Images can be used to support textual communication (with visual communication).
* Large (content-wide) images should be used sparingly.

## 3. Rules 
* The preparation of pictures and illustrations is regulated by the specifications of KOM (see links).
* Use illustrations and infographics as SVG, ensure high enough resolution for all screen sizes for photographs.
* Apart from the red SBB panel, pictures may not contain any overlays.
* Only context-relevant images may be used (the image must match the content).
* Combining different styles can positively influence the UX (photography for realities, illustrations for concepts)
* Different image sizes can help to emphasize (prioritize) the importance of images.
* Optionally, images can have a description text (caption).

## 4. Variants and states
The following styles are distinguished for images:
* Photography.
* Illustration.
* Infographics.

Bei Bildern werden folgende Stile unterschieden:
* Fotografie
* Illustration
* Infografik

### 4.1 Key Visual
* Use only photographs (not illustrations).
* Key visuals do not contain information.
* Key visuals can be static images or videos. Animated GIFs are not possible.
    * Pictures and videos are always treated equally.
* Key visuals never have captions or copyright information.
* Key visuals have a fixed format for each end device, the image section adapts to the viewport.
* Key visuals can be implemented as Mediasliders.
* No description text is allowed.

### Formats
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


## 4.2 Info picture 
* Infopictures can be static images, animated GIFs or videos.
    * Static images, animated GIFs and videos are always treated equally.
* Infopictures can optionally have a caption and copyright information below the picture.
    * Recommended text length of the caption including copyright info should be 2 lines on desktop at max.
* Infopictures must not use a panel.
* Infopictures are never linked.
* Infopictures always have the format 16:9.
* Infopictures do not have a fullscreen view.

## 4.3 Lazyload
* If there are many images on a page, then images are lazyloaded outside the viewport.

## 4.4 Inside of a teaser
* Pictures are slightly zoomed on hover.

## 4.5 As background (e.g. map)
* Scrolling down zooms in, scrolling up zooms out.
* The image should cover the entire viewport of the content area.
* Text and interaction elements (buttons) above the image are allowed.
* Important: always comply with minimal contrasts → Images should contain dark colors so that text in white can be used as overlay.