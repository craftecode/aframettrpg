Tried out Atlas UVs and it worked for test but didn't work with transparancy that I was trying for displaying paper minis. I just used the both directions option on a plane.
```html
<script src="https://unpkg.com/aframe-atlas-uvs-component@^1.0.0/dist/aframe-atlas-uvs-component.min.js"></script>

<a-mixin
          id="myAtlas"
          atlas-uvs="totalRows: 4; totalColumns: 4"
          material="src: https://cdn.glitch.com/3abf7543-e204-453e-930e-52da666500f0%2Ftextures2.png"
          geometry="primitive: plane; buffer: false; skipCache: true"
        ></a-mixin>
        
        <a-mixin
          id="myAtlas02"
          atlas-uvs="totalRows: 2; totalColumns: 1"
          material="src: https://cdn.glitch.com/3abf7543-e204-453e-930e-52da666500f0%2Fprintableheroes_bugbear01.png; transparent: true"
          geometry="primitive: plane; buffer: false; skipCache: true"
        ></a-mixin>
        ```
