---
title: My Building Block (Schema)

language_tabs:
  - shell
  - python: Python
  - javascript: Javascript

toc_footers:
  - Version 0.1
  - <a href='#'>My Building Block</a>
  - <a href='https://blocks.ogc.org/register.html'>Building Blocks register</a>

search: true

code_clipboard: true

meta:
  - name: My Building Block (Schema)
---


# My Building Block `avillar.sandbox.my-building-block`

This Building Block serves as a template to create new ones

<p class="status">
    <span data-rainbow-uri="http://www.opengis.net/def/status">Status</span>:
    <a href="http://www.opengis.net/def/status/under-development" target="_blank" data-rainbow-uri>Under development</a>
</p>

<aside class="success">
This building block is <strong><a href="https://github.com/avillar/bblocks-sandbox-nopages/blob/master/build/tests/sandbox/my-building-block/" target="_blank">valid</a></strong>
</aside>

# Description

## Qui hastarum tectus Cithaeron iuvabat

Lorem markdownum vestigia sanguine rursus undis, suspenderat meo mox conlegerat
temperat sucos. Est graves dant sentire sanguinis flores respondent testari.

** This is a relative URL: [example.png](assets/example.png) **.

![Image](assets/example.png)

> Videri vias quid Ausoniae sua flores ante, reminiscitur fuit est. Semel
> [hectora](http://silvaque.org/) peregrinaeque rudem exercent in, Troiana si
> Asida instabilesque somno sed.

## Iam vota cui dilataque peterem

Tinxit lumina lacer liquidarum Aiax si mergitur sed fueris capitisque **et
cadit** contigerant rectum [ferar](http://prosternit.com/quoque.html) temperat.
Monet caput adsensere Ityn furentibus gelidos.
# Examples

## This is an example with just a description and no code snippets.

This is the content of the example.

In **Markdown** format.

** This is a relative URL: [example.png](assets/example.png) **.

![Image](assets/example.png)


## Examples can have content and/or code snippets.



```shell
echo 'Hello, world!'
```



```python
print('Hello, world!')
```



```javascript
console.log('Hello, world!')
```

The content of this example. 

** This is a relative URL: [example.png](assets/example.png) **.

![Image](assets/example.png)


# JSON Schema

```yaml--schema
$schema: https://json-schema.org/draft/2020-12/schema
description: Schema for my building block
type: object
definitions:
  test:
    type: string
properties:
  a:
    type: string
    format: uri
    x-jsonld-id: https://example.org/my-bb-model/a
    x-jsonld-type: '@id'
  b:
    type: number
    x-jsonld-id: https://example.org/my-bb-model/b
  c:
    $ref: https://raw.githubusercontent.com/avillar/bblocks-sandbox-nopages/undefined/build/annotated/sandbox/my-building-block/schema.yaml#/definitions/test
  d:
    $ref: https://raw.githubusercontent.com/avillar/bblocks-sandbox-nopages/undefined/build/annotated/sandbox/enumerations/legalStatus/schema.yaml
required:
- a
- b

```

> <a target="_blank" href="https://avillar.github.io/TreedocViewer/?dataParser=yaml&amp;dataUrl=https%3A%2F%2Fraw.githubusercontent.com%2Favillar%2Fbblocks-sandbox-nopages%2Fundefined%2Fbuild%2Fannotated%2Fsandbox%2Fmy-building-block%2Fschema.yaml&amp;expand=2&amp;option=%7B%22showTable%22%3A+false%7D">View on YAML Viewer</a>

Links to the schema:

* YAML version: <a href="https://raw.githubusercontent.com/avillar/bblocks-sandbox-nopages/undefined/build/annotated/sandbox/my-building-block/schema.yaml" target="_blank">https://raw.githubusercontent.com/avillar/bblocks-sandbox-nopages/undefined/build/annotated/sandbox/my-building-block/schema.yaml</a>
* JSON version: <a href="https://raw.githubusercontent.com/avillar/bblocks-sandbox-nopages/undefined/build/annotated/sandbox/my-building-block/schema.json" target="_blank">https://raw.githubusercontent.com/avillar/bblocks-sandbox-nopages/undefined/build/annotated/sandbox/my-building-block/schema.json</a>


# JSON-LD Context

```json--ldContext
{
  "@context": {
    "a": {
      "@id": "https://example.org/my-bb-model/a",
      "@type": "@id"
    },
    "b": "https://example.org/my-bb-model/b",
    "@version": 1.1
  }
}
```

> <a target="_blank" href="https://json-ld.org/playground/#json-ld=https%3A%2F%2Fraw.githubusercontent.com%2Favillar%2Fbblocks-sandbox-nopages%2Fundefined%2Fbuild%2Fannotated%2Fsandbox%2Fmy-building-block%2Fcontext.jsonld">View on JSON-LD Playground</a>

You can find the full JSON-LD context here:
<a href="https://raw.githubusercontent.com/avillar/bblocks-sandbox-nopages/undefined/build/annotated/sandbox/my-building-block/context.jsonld" target="_blank">https://raw.githubusercontent.com/avillar/bblocks-sandbox-nopages/undefined/build/annotated/sandbox/my-building-block/context.jsonld</a>

# References

* [Sample source document](https://example.com/sources/1)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: <a href="https://github.com/avillar/bblocks-sandbox-nopages" target="_blank">https://github.com/avillar/bblocks-sandbox-nopages</a>
* Path:
<code><a href="https://github.com/avillar/bblocks-sandbox-nopages/blob/HEAD/_sources/my-building-block" target="_blank">_sources/my-building-block</a></code>

