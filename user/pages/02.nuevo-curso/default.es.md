---
title: 'Nuevo Curso'
published: true
routable: true
visible: false
template: form
admin:
    children_display_order: collection
pageconfig:
    parent: /
pagefrontmatter:
    visible: true
    status: draft
    template: default
    course:
        assignment: 'CMPT363 E100'
    instructor:
        name: 'Jane Doe'
form:
    name: addpage-assignment-cmpt363-e100
    fields:
        -
            name: title
            label: Título
            type: text
            validate:
                required: true
        -
            name: content
            label: Contenido
            type: textarea
            size: long
            classes: editor
            validate:
                required: true
        -
            name: attachments
            label: 'Multimedia de página'
            type: file
            multiple: true
            accept:
                - application/pdf
            validate:
                required: false
        -
            name: honeypot
            type: honeypot
    buttons:
        -
            type: submit
            value: Submit
    process:
        -
            addpage: null
        -
            redirect: '@self'
---

