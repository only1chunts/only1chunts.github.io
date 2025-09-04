---
layout: items
title: Chris Hunter
tags: news, blog
date: 2025-09-04
---

{% include head.html %} 

here it is:
<ui>
  {% for post in site.posts %}
	{{ post.date | date: "%-d %B %Y" }} <a href="{{ post.url }}">{{ post.excerpt }} </a>
        <br>
  {% endfor %}
</ui>

<div id="GigaDB-metadata-guide_31085" align="center" x:publishsource="Excel">

<table border="0" cellpadding="0" cellspacing="0" width="1082" style="border-collapse:
 collapse;table-layout:fixed;width:812pt"><colgroup><col class="xl7031085" width="173" style="mso-width-source:userset;mso-width-alt:
 6326;width:130pt"> <col class="xl6631085" width="519" style="mso-width-source:userset;mso-width-alt:
 18980;width:389pt"> <col class="xl6331085" width="102" style="mso-width-source:userset;mso-width-alt:
 3730;width:77pt"> <col class="xl6631085" width="288" style="mso-width-source:userset;mso-width-alt:
 10532;width:216pt"></colgroup>

<tbody>

<tr height="60" style="height:45.0pt">

<td height="60" class="xl6431085" width="173" style="height:45.0pt;width:130pt">Field</td>

<td class="xl6531085" width="519" style="border-left:none;width:389pt">Definition with tips</td>

<td class="xl6531085" width="102" style="border-left:none;width:77pt">required/ recommended/ optional</td>

<td class="xl6531085" width="288" style="border-left:none;width:216pt">example</td>

</tr>

<tr height="20" style="height:15.0pt">

<td height="20" class="xl7131085" style="height:15.0pt;border-top:none">DOI</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">Digital object identifier, <font class="font531085">assigned by GigaDB</font></td>

<td class="xl6831085" style="border-top:none;border-left:none">Required</td>

<td class="xl7531085" width="288" style="border-top:none;border-left:none;
  width:216pt">10.5524/100473</td>

</tr>

<tr height="80" style="height:60.0pt">

<td height="80" class="xl7131085" style="height:60.0pt;border-top:none">Title</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">The title of the dataset, this should be distinguishable from any associated manuscript publication, often this is achieved by prefixing the manuscript title with the term "Supporting data for". For technical reasons we use HTML encoding within the title field for all formatting, including bold and italics.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Required</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">Supporting data for "SVEngine: an efficient and versatile simulator of genome structural variations with features of cancer clonal evolution"</td>

</tr>

<tr height="80" style="height:60.0pt">

<td height="80" class="xl7131085" style="height:60.0pt;border-top:none">Description</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">Summary describing the purpose, nature, and scope of the Dataset. Often this is the same as the abstract of the associated manuscript. For technical reasons we use HTML encoding within the description block for all formatting, including line breaks, bold, italics and hyperlinks, GigaDB staff can assist with this.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Required</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">This could be several paragraphs in length.<span style="mso-spacerun:yes"></span> Line returns are included in the description as HTML tags "<br>".</td>

</tr>

<tr height="20" style="height:15.0pt">

<td height="20" class="xl7131085" style="height:15.0pt;border-top:none">Authors</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">Person(s) responsible for creating the work. Consists of 2 subfields</td>

<td class="xl6831085" style="border-top:none;border-left:none">Required</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt"> </td>

</tr>

<tr height="60" style="height:45.0pt">

<td height="60" class="xl7231085" style="height:45.0pt;border-top:none">Name</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">The author's Family Name, Middle Name or Initials, Given Name.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Required</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">Xia, C, Li; Ai, Dongmei; Lee, Hojoon; Andor, Noemi;Li, Chao; Zhang, R, Nancy; Ji, P, Hanlee</td>

</tr>

<tr height="60" style="height:45.0pt">

<td height="60" class="xl7231085" style="height:45.0pt;border-top:none">ORCID</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">If the author has an ORCID it can be added here. ORCID is a non-proprietary alphanumeric code to identify scientific and other academic authors and contributors uniquely.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Optional</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">0000-0001-2345-6789;</td>

</tr>

<tr height="20" style="height:15.0pt">

<td height="20" class="xl7131085" style="height:15.0pt;border-top:none">Contact author</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">Contact author for this Dataset. Consists of 3 subfields.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Required</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt"> </td>

</tr>

<tr height="20" style="height:15.0pt">

<td height="20" class="xl7231085" style="height:15.0pt;border-top:none">Name</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">The contact/submitting author's Family Name and Given Name.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Required</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">Ji, Hanlee</td>

</tr>

<tr height="20" style="height:15.0pt">

<td height="20" class="xl7231085" style="height:15.0pt;border-top:none">Affiliation</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">The contact/submitting author's affiliation name and location</td>

<td class="xl6831085" style="border-top:none;border-left:none">Required</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">Stanford, USA</td>

</tr>

<tr height="20" style="height:15.0pt">

<td height="20" class="xl7231085" style="height:15.0pt;border-top:none">Email</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">The contact/submitting author's email address.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Required</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">genomics_ji@***nford.edu</td>

</tr>

<tr height="20" style="height:15.0pt">

<td height="20" class="xl7131085" style="height:15.0pt;border-top:none">Publication date</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">Date that the dataset was made publicly available. (YYYY-MM-DD)</td>

<td class="xl6831085" style="border-top:none;border-left:none">Required</td>

<td class="xl6931085" width="288" style="border-top:none;border-left:none;
  width:216pt">2018-06-21</td>

</tr>

<tr height="60" style="height:45.0pt">

<td height="60" class="xl7131085" style="height:45.0pt;border-top:none">Dataset type (subject)</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">Domain-specific Subject Categories that are topically relevant to the Dataset. There is a controlled vacobulary of terms supplied by GigaDB (http://gigadb.org/site/help#vocabulary)</td>

<td class="xl6831085" style="border-top:none;border-left:none">Required</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">Genomic; Software</td>

</tr>

<tr height="60" style="height:45.0pt">

<td height="60" class="xl7131085" style="height:45.0pt;border-top:none">keywords</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">Key terms that describe important aspects of the Dataset. All keywords are stored and presented in lower-case regardless of acronyms of any other prefered capitalization.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Recommended</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">structural variation; next generation sequencing; sequence analysis</td>

</tr>

<tr height="60" style="height:45.0pt">

<td height="60" class="xl7131085" style="height:45.0pt;border-top:none">Thumbnail image (logo)</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">Optional addition of an image to enhance dataset landing page. If no appropriate image is available then a generic "no image" logo will be used. Consists of 4 subfields.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Optional</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt"> </td>

</tr>

<tr height="40" style="height:30.0pt">

<td height="40" class="xl7231085" style="height:30.0pt;border-top:none">logo description</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">Short name and/or description of the thumbnail image, particularly useful if this is a figure from the associated manuscript</td>

<td class="xl6831085" style="border-top:none;border-left:none">Optional</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">Fig1: Inputs, outputs, and execution components of SVEngine.</td>

</tr>

<tr height="40" style="height:30.0pt">

<td height="40" class="xl7231085" style="height:30.0pt;border-top:none">logo license</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">All images used must be openly licensed, preferably CC0 or public domain, but CC-BY is also acceptable.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Optional</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">CC0</td>

</tr>

<tr height="20" style="height:15.0pt">

<td height="20" class="xl7231085" style="height:15.0pt;border-top:none">logo source</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">Name or URL of the source of the image used</td>

<td class="xl6831085" style="border-top:none;border-left:none">Optional</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">Xia et al. 2018</td>

</tr>

<tr height="40" style="height:30.0pt">

<td height="40" class="xl7231085" style="height:30.0pt;border-top:none">logo credit</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">Name of person to credit for the logo or image, this could be the photographers name if it’s a photograph.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Optional</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">Xia et al. 2018</td>

</tr>

<tr height="40" style="height:30.0pt">

<td height="40" class="xl7131085" style="height:30.0pt;border-top:none">Related publication(s)</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">The DOI of the Publication(s) that uses or describes the generation of the data in this Dataset. i.e. the publication which this dataset accompanies.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Recommended</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">doi:10.1093/gigascience/giy081</td>

</tr>

<tr height="20" style="height:15.0pt">

<td height="20" class="xl7131085" style="height:15.0pt;border-top:none">Related materials</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">Any material related to this Dataset.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Optional</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">https://bitbucket.org/charade/svengine</td>

</tr>

<tr height="60" style="height:45.0pt">

<td height="60" class="xl7131085" style="height:45.0pt;border-top:none">Externally hosted materials</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">If parts of this dataset are hosted by other repositories, e.g. GitHub, Zenodo, Dryad, Figshare etc, we do not need to duplicate those data, simply add the direct link here.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Optional</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">https://github.com/gigascience/gigadb-website</td>

</tr>

<tr height="40" style="height:30.0pt">

<td height="40" class="xl7131085" style="height:30.0pt;border-top:none">Umbrella project name</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">If this dataset was produced under the auspicies of an international collaboration the name of that project may be included here.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Optional</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">1000 Genomes</td>

</tr>

<tr height="40" style="height:30.0pt">

<td height="40" class="xl7131085" style="height:30.0pt;border-top:none">Related GigaDB datasets</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">Any GigaDB dataset(s) that are related to this Dataset, such as previous releases, or subsets of the Dataset.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Optional</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">IsNewVersionOf:100123</td>

</tr>

<tr height="60" style="height:45.0pt">

<td height="60" class="xl7431085" width="173" style="height:45.0pt;border-top:none;
  width:130pt">Externally hosted data accessions</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">If raw data generated or used in this dataset are hosted by other repositories, e.g. SRA, ProteomeXchange etc, we do not need to duplicate those data, simply add the accession number here.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Optional</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">BioProject:PRJNA012345</td>

</tr>

<tr height="40" style="height:30.0pt">

<td height="40" class="xl7131085" style="height:30.0pt;border-top:none">Grant information</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">We collect Information about grants utilised during the collection and analysis of this dataset. Consists of 4 subfields.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Optional</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt"> </td>

</tr>

<tr height="40" style="height:30.0pt">

<td height="40" class="xl7231085" style="height:30.0pt;border-top:none">Agency name</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">Name of the funding agency providing the sponsorship or funding. When possible this should be from the FundRef* list of funding bodies.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Recommended</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">National Cancer Institute</td>

</tr>

<tr height="20" style="height:15.0pt">

<td height="20" class="xl7231085" style="height:15.0pt;border-top:none">Grant number</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">The grant or contract number of the project that sponsored the effort.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Recommended</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">U01CA15192001</td>

</tr>

<tr height="20" style="height:15.0pt">

<td height="20" class="xl7231085" style="height:15.0pt;border-top:none">Awardee</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">The name of the person responsible for getting the award</td>

<td class="xl6831085" style="border-top:none;border-left:none">Recommended</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">N Andor</td>

</tr>

<tr height="40" style="height:30.0pt">

<td height="40" class="xl7231085" style="height:30.0pt;border-top:none">Comment</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">Some agencies have multiple award programs through which they distribute funding, if appropriate that information can be added here.</td>

<td class="xl6831085" style="border-top:none;border-left:none">Optional</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt">Cancer Target Discovery and Development (CTDD) Consortium</td>

</tr>

<tr height="60" style="height:45.0pt">

<td height="60" class="xl7131085" style="height:45.0pt;border-top:none">Additional information</td>

<td class="xl6731085" width="519" style="border-top:none;border-left:none;
  width:389pt">We are able to hold any additional information in GigaDB using user-defined key-value pairs, however at time of writing this we have no display mechanism for such details.</td>

<td class="xl7331085" width="102" style="border-top:none;border-left:none;
  width:77pt">feature not available yet</td>

<td class="xl6731085" width="288" style="border-top:none;border-left:none;
  width:216pt"> </td>

</tr>

<tr height="0" style="display:none">

<td width="173" style="width:130pt"></td>

<td width="519" style="width:389pt"></td>

<td width="102" style="width:77pt"></td>

<td width="288" style="width:216pt"></td>

</tr>

</tbody>

</table>

</div>
