---
title: Cartesian and IDEX
badges:
    - Official
uid: EVA / Addons / Cartesian-IDEX
type: addon
contributors: 
    - pkucmus
repo_url: https://github.com/EVA-3D/addon-cartesian-idex
cad_url: https://cad.onshape.com/documents/a2d21b0faa4745fa21bc844e/w/d7f14dfeeee2e68fe2f1149b/e/fcd1503d3995b7b7473cc831
---
# Cartesian and IDEX support

EVA 2 supports not only CoreXY printers. You can also use it on a 6mm belt cartesian or even IDEX system.

??? warning "IDEX Z offset caveat"

    Z offset regulation is not figured out yet - as of today the assumption (as unrealistic as it maybe) is that the tips of both nozzles are at the same Z offset.

??? info "Front belt holders"

    On a cartesian/IDEX type EVA the front belt holders are reundant - there are no belts in the front.

![preview](assets/__ALL__.png)

### BOM

=== "Cartesian"

    <add-bom-button name="{{ meta.uid }} (cartesian)">
        {{ bom_to_json("cartesian.csv") }}
    </add-bom-button>

    ![preview](assets/cartesian.png)

    {{ bom_to_md_table("cartesian.csv", 8) }}

=== "IDEX X1"

    <add-bom-button name="{{ meta.uid }} (idex_x1)">
        {{ bom_to_json("idex_x1.csv") }}
    </add-bom-button>

    ![preview](assets/idex_x1.png)

    {{ bom_to_md_table("idex_x1.csv", 8) }}

=== "IDEX X2"

    <add-bom-button name="{{ meta.uid }} (idex_x2)">
        {{ bom_to_json("idex_x2.csv") }}
    </add-bom-button>

    ![preview](assets/idex_x2.png)

    {{ bom_to_md_table("idex_x2.csv", 8) }}

### Links

{{ download_button }}
{{ cad_link }}
