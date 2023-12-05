<link rel="stylesheet" href="table_hide.css"/>
<div class="metadata">
   <h2>Metadata</h2>
   <dl class="grid">
      <dt>Name:</dt>
      <dd>GT-FRAKTUR</dd>
      <dt>Description:</dt>
      <dd>This repository contains transcriptions of selected pages from 19th Century books. The original TIFF images used for OCR transcription of the following publications are published on Archive.org.</dd>
      <dt>Language:</dt>
      <dd>deu</dd>
      <dt>Format:</dt>
      <dd>Page-XML</dd>
      <dt>Production software:</dt>
      <dd>Transkribus</dd>
      <dt>Time:</dt>
      <dd>1834-1875</dd>
      <dt>GT Type:</dt>
      <dd>data_structure_and_text</dd>
   </dl>
   <details>
      <summary>More Information</summary>
      <dl class="more-grid">
         <dt>License:</dt>
         <dd>CC0 1.0</dd>
      </dl>
   </details>
</div>
<div class="metadata">
   <h2>Labelling</h2>
   <p>The GT data has been labeled. The labeling is 
               based on an ontology defined by the Pattern Recognition and Image Analysis Research Lab 
               (PRImA-Research-Lab) at the University of Salford. 
               This normalized and semantic description of the OCR-GT data can be found in the METS metadata file. 
               The labeling metadata is created for each available page. The following labeling metadata is available for the complete collection.</p>
   <p>Here you will find a description and explanation of the labeling metadata.</p>
   <details>
      <summary>activityDomain/computing/visual/analysisRecognition/layoutAnalysis</summary>
      <p>
         <strong>Description: </strong>In computer vision, document layout analysis is the process of identifying and categorizing the regions of interest in the scanned image of a text document. A reading system requires the segmentation of text zones from non-textual ones and the arrangement in their correct reading order.

Examples:
Page layout analysis (segmentation into regions, classification into text, graphic, table etc.)

Related:
"OCR": Often used as a synonym for layout analysis and text recognition, but strictly only the text recognition component.</p>
   </details>
   <details>
      <summary>activityDomain/computing/visual/analysisRecognition/ocr</summary>
      <p>
         <strong>Description: </strong>
      </p>
   </details>
   <details>
      <summary>activityDomain/computing/visual/analysisRecognition/text</summary>
      <p>
         <strong>Description: </strong>Translation of any kind of depicted symbols to machine readable format

Examples:
OCR
Mathematical equation recognition

Related:
Text processing (separate category)
Table recognition
Map reading</p>
   </details>
   <details>
      <summary>content-encoding/structured</summary>
      <p>
         <strong>Description: </strong>E.g. XML</p>
   </details>
   <details>
      <summary>content-type/corpus</summary>
      <p>
         <strong>Description: </strong>
Corpus: a collection of written texts, especially the entire works of a particular author or a body of writing on a particular subject.

Examples:
A text corpus,
An image database</p>
   </details>
   <details>
      <summary>contentOfInterest/visual/text</summary>
      <p>
         <strong>Description: </strong>
                        Description coming soon.
                    </p>
   </details>
   <details>
      <summary>data-attributes/document-related/visual/text/font/typeface/antiqua</summary>
      <p>
         <strong>Description: </strong>Antiqua font (more modern)</p>
   </details>
   <details>
      <summary>data-attributes/document-related/visual/text/font/typeface/blackletter</summary>
      <p>
         <strong>Description: </strong>Blackletter, gothic, Fraktur</p>
   </details>
   <details>
      <summary>granularity/physical/document-related/page</summary>
      <p>
         <strong>Description: </strong>
                        Description coming soon.
                    </p>
   </details>
   <details>
      <summary>granularity/physical/document-related/text-line</summary>
      <p>
         <strong>Description: </strong>
                        Description coming soon.
                    </p>
   </details>
   <details>
      <summary>granularity/physical/document-related/word</summary>
      <p>
         <strong>Description: </strong>Word or partial word, if separated by line break, for example</p>
   </details>
   <details>
      <summary>platform/platform-independent</summary>
      <p>
         <strong>Description: </strong>
                        Description coming soon.
                    </p>
   </details>
</div>
<div class="metadata">
   <h2>Download</h2>
   <p>You can download the complete data here. 
                        They contain a zip file in which the components of the collection are also in zip files.
                        Metadata for the complete collection and the components are in METS format.</p>
   <ul>
      <li>
         <a href="https://github.com/tboenig/gt-fraktur/releases/tag/v1.0.9">The BagIt 'ocrd.zip' files for the current version, please download them from the latest release.: Release 10_v1.0.9</a>
      </li>
      <li>
         <a href="https://github.com/tboenig/gt-fraktur/releases">Version archive</a>
      </li>
   </ul>
</div>
<div class="metadata">
   <h2>Total view</h2>
   <table class="noStyle">
      <tr>
         <td>💡 You can show and hide individual columns of the table.<br/>Click the corresponding button.
                                <details>
               <summary>Legend</summary>
               <dl class="grid">
                  <dt>TextLine</dt>
                  <dd>TextLine</dd>
                  <dt>Page</dt>
                  <dd>Page</dd>
                  <dt>TxtRegion</dt>
                  <dd>
                     <a href="https://ocr-d.de/de/gt-guidelines/trans/lytextregion.html"
                        target="_blank">TextRegion</a>
                  </dd>
               </dl>
            </details>
         </td>
         <td>
            <div class="grid-container">
               <button onclick="document.getElementById('table_id').classList.toggle('hide1')">
                  <i>TextLine</i>
               </button>
               <button onclick="document.getElementById('table_id').classList.toggle('hide2')">
                  <i>Page</i>
               </button>
               <button onclick="document.getElementById('table_id').classList.toggle('hide3')">
                  <i>TxtRegion</i>
               </button>
            </div>
         </td>
      </tr>
   </table>
   <table id="table_id">
      <thead>
         <tr>
            <th>TextLine</th>
            <th>Page</th>
            <th>TxtRegion</th>
         </tr>
      </thead>
      <tbody>
         <tr>
            <td>14662</td>
            <td>208</td>
            <td>491</td>
         </tr>
      </tbody>
   </table>
</div>
<div>
   <h2>Details</h2>
   <ul>
      <li>
         <a href="table">Compressed table view</a>
      </li>
      <li>
         <a href="overview">Detailed table view</a>
      </li>
   </ul>
</div>
