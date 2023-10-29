# vb-book6

Editing Venetus B, book 6



## How to validate


#### Starting from the command line

From a terminal open in this directory, you can start the validating dashboard with:

    julia --project=dashboard dashboard/validatordashboard.jl


(Note that in VS Code, you can use `New Terminal` from the `Terminal` menu to open a terminal in the directory you're editing.)

#### Viewing the dashboard

Open a browser to `http://localhost:8051`.

1. Use the `Load/update data` button to load or reload the current data in your repository.  
2. Select a page from the drop-down menu.  If you have errors or incomplete work, repeat these two steps after making your corrections.


## URNs: quick reference


- **texts**
    - scholia: `urn:cts:greekLit:tlg5026.msB.hmt:` with passage identifiers like `9.115r_1` for *book/scholion*
    - *Iliad*:  `urn:cts:greekLit:tlg0012.tlg001.msB:`  with identifiers like `9.1` for *book/line*
    - *metrical summaries*: `urn:cts:greekLit:tlg7000.tlg001.msB:`
- **MS pages**: collection `urn:cite2:hmt:msB.v1:` with identifiers like `1r` identifying a single *page*
- **images**: collection `urn:cite2:hmt:vbbifolio.v1:` with identifiers like `vb_114v_115r` identifying images of *bifolio spreads*


