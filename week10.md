## Advanced Archival Description

### HIST GA 2031

* * *

Structure Standards



# What is metadata?



## Structure Standards

Machine-readable  
Community-based  
Facilitate transmission across geographic distance (web discovery)  
Support shared tools



# MARC



  ![marc overview](lectures/img/marc-overview.png)



  <span class="marc-field">245</span>  <span class="marc-indicator">10</span>  <span class="marc-delimiter">|</span><span class="marc-subfield">a</span> American Federation of Musicians, Local 802 Records <span class="marc-delimiter">|</span><span class="marc-subfield">f</span> 1921-2010 <span class="marc-delimiter">|</span><span class="marc-subfield">g</span> (Bulk 1980s-1990s)




<span class="marc-field">245</span>  <span class="marc-indicator">10</span>  <span class="marc-delimiter">|</span><span class="marc-subfield">a</span> American Federation of Musicians, Local 802 Records <span class="marc-delimiter">|</span><span class="marc-subfield">f</span> 1921-2010 <span class="marc-delimiter">|</span><span class="marc-subfield">g</span> (Bulk 1980s-1990s)

<span class="marc-field">Field</span>  
<span class="marc-indicator">Indicator</span>  
<span class="marc-delimiter">Delimiter</span>  
<span class="marc-subfield">Subfield Code</span>



## XML
Standard Generalized Markup Language (SGML) - 1986  
Extensible Markup Language (XML) - 1998  
Document Type Definition (DTD)  
Schema



<<span class="xml-tag">[tag]</span> <span class="xml-attribute">[attribute]</span>="<span class="xml-value">[value]</span>">content</<span class="xml-tag">[tag]</span>>



<<span class="xml-tag">unitdate</span> <span class="xml-attribute">type</span>="<span class="xml-value">inclusive</span>">1937-1992</<span class="xml-tag">unitdate</span>>

<<span class="xml-tag">origination</span> <span class="xml-attribute">label</span>="<span class="xml-value">Creator</span>">Kenny, Elizabeth</<span class="xml-tag">origination</span>>

<<span class="xml-tag">unittitle</span> <span class="xml-attribute">encodinganalog</span>="<span class="xml-value">MARC 245</span>" <span class="xml-attribute">label</span>="<span class="xml-value">Title</span>">Elizabeth Kenny Papers</<span class="xml-tag">unittitle</span>>



## Your turn!

<code style="font-size:.6em;">`<unitdate normal="1879/1894" type="bulk">bulk</unitdate>`</code>

<code style="font-size:.6em;">`<persname role="ctb" source="lcnaf">Inglis, William O.</persname>`</code>



## EAD
Originally developed in 1998, revised in 2002 and 2015  
An XML DTD  
Applies semantic meaning to content



## Structure

```
<eadheader>...</eadheader>
<frontmatter>...</frontmatter>
<archdesc>
  <dsc>
    <c>...</c>
  </dsc>
</archdesc>
```



## EAC-CPF
Developed in 2011, under review (major and minor updates)
An XML Schema  
Used mostly in large consortia



## Structure

```
<control/>
<cpfDescription/>
```
or
```
<control>...</control>
<multipleIdentities>
  <cpfDescription>...</cpfDescription>
  <cpfDescription>...</cpfDescription>
</multipleIdentities>
```
