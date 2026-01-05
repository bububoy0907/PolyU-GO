```
<a-entity
        gltf-model="#gh_model"
        scale="1.5 1.5 1.5"
        rotation="90 0 0"
        animation="property: rotation; to: 90 360 0; loop: true; dur: 10000; easing: linear"
        animation__updown="property: position; to: -0.5 3 0; dir: alternate; loop: true; dur: 2000; easing: easeInOutSine"
        position="-0.5 2.8 0"
        material="color: #FFFFFF; shader: flat;">
      </a-entity>


//action: can move up and down with rotation, the model has Self-illuminating source which is setted in blender, all model are designed with same scale and color
```
