---
title: Contact
layout: default
---
<p>Add me to your Contacts.</p>

<style>
    .vcard.download {
        position: relative;
        margin: 2em 0;
        padding: 1em;
        border: 1px dotted #dfdfdf;
        background: #efefef;
        box-shadow: #ccc .5em .5em .5em;
        border-radius: 12px;
        max-width: 300px;
        border-radius: 0;
        border: 1px dashed #999;
        background: #fff;
        box-shadow: none;
    }

    a.vcard.download {
        display: block;
        text-decoration: none;
        color: #000;
    }

    a.vcard.download:after {
        content: "\2709";
        color: #000;
        font-size: 3em;
        top: -.2em;
        right: .25em;
        position: absolute;
    }

    a.vcard.download:after {
        color: #000;
        content: "\2b07";
        font-weight: bold;
        font-size: 1.5em;
        top: .5em;
        right: .5em;
        border-bottom: solid 3px;
        line-height: 1.1
    }

    a.vcard.download:hover,
    a.vcard.download:hover:after {
        background: #efefef;
        color: #333
    }

    .vcard.download p {
        padding: 0;
        margin: 0;
    }

    .vcard.download .email {
        font-weight: bold
    }

    .vcard.download .category {
        font-style: italic;
    }

    .vcard.download a[type="download"] {
        position: absolute;
        top: -.2em;
        right: .25em;
        font-size: 3em;
        text-decoration: none;
        color: #000;
    }

    .vcard.download a[type="download"]:hover {
        color: #999;
    }

    /* mobile */
    @media (max-width: 414px) {
        .vcard.download {
            max-width: 100%;
        }
    }
</style> 

<div>
<a type="download" href="doug-hamaker.vcf" title="Import to Contacts" class="vcard download">
    <p class="fn">Doug Hamaker</p>
    <p class="category">User Experience Manager</p>
    <p class="email">&#100;hamaker&#64;lmi&#46;net</p>
</a>
</div>