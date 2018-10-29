# Namespace: PIXI

## PIXI

<dl>
                    <dt>Source:</dt>
                    <dd>
                        <ul>
                            <li>
                                <a>libs/pixi.js</a>, <a>line 12838</a>
                            </li>
                        </ul>
                    </dd>
                </dl>

### Classes

<dl>
                    <dt><a>AccessibilityManager</a></dt>
                    <dd></dd>
                    <dt><a>BaseRenderTexture</a></dt>
                    <dd></dd>
                    <dt><a>BaseTexture</a></dt>
                    <dd></dd>
                    <dt><a>Bounds</a></dt>
                    <dd></dd>
                    <dt><a>CanvasExtract</a></dt>
                    <dd></dd>
                    <dt><a>CanvasMaskManager</a></dt>
                    <dd></dd>
                    <dt><a>CanvasPrepare</a></dt>
                    <dd></dd>
                    <dt><a>CanvasRenderer</a></dt>
                    <dd></dd>
                    <dt><a>CanvasRenderTarget</a></dt>
                    <dd></dd>
                    <dt><a>Circle</a></dt>
                    <dd></dd>
                    <dt><a>Container</a></dt>
                    <dd></dd>
                    <dt><a>createIndicesForQuads</a></dt>
                    <dd></dd>
                    <dt><a>DisplayObject</a></dt>
                    <dd></dd>
                    <dt><a>Ellipse</a></dt>
                    <dd></dd>
                    <dt><a>Filter</a></dt>
                    <dd></dd>
                    <dt><a>FilterManager</a></dt>
                    <dd></dd>
                    <dt><a>FXAAFilter</a></dt>
                    <dd></dd>
                    <dt><a>Graphics</a></dt>
                    <dd></dd>
                    <dt><a>GraphicsData</a></dt>
                    <dd></dd>
                    <dt><a>GraphicsRenderer</a></dt>
                    <dd></dd>
                    <dt><a>mapWebGLDrawModesToPixi</a></dt>
                    <dd></dd>
                    <dt><a>MaskManager</a></dt>
                    <dd></dd>
                    <dt><a>Matrix</a></dt>
                    <dd></dd>
                    <dt><a>ObjectRenderer</a></dt>
                    <dd></dd>
                    <dt><a>ObservablePoint</a></dt>
                    <dd></dd>
                    <dt><a>ParticleShader</a></dt>
                    <dd></dd>
                    <dt><a>Point</a></dt>
                    <dd></dd>
                    <dt><a>Polygon</a></dt>
                    <dd></dd>
                    <dt><a>PrimitiveShader</a></dt>
                    <dd></dd>
                    <dt><a>Quad</a></dt>
                    <dd></dd>
                    <dt><a>Rectangle</a></dt>
                    <dd></dd>
                    <dt><a>RenderTarget</a></dt>
                    <dd></dd>
                    <dt><a>RenderTexture</a></dt>
                    <dd></dd>
                    <dt><a>RoundedRectangle</a></dt>
                    <dd></dd>
                    <dt><a>Shader</a></dt>
                    <dd></dd>
                    <dt><a>Sprite</a></dt>
                    <dd></dd>
                    <dt><a>SpriteMaskFilter</a></dt>
                    <dd></dd>
                    <dt><a>StencilManager</a></dt>
                    <dd></dd>
                    <dt><a>SystemRenderer</a></dt>
                    <dd></dd>
                    <dt><a>Text</a></dt>
                    <dd></dd>
                    <dt><a>TextStyle</a></dt>
                    <dd></dd>
                    <dt><a>Texture</a></dt>
                    <dd></dd>
                    <dt><a>TextureGarbageCollector</a></dt>
                    <dd></dd>
                    <dt><a>TextureManager</a></dt>
                    <dd></dd>
                    <dt><a>Transform</a></dt>
                    <dd></dd>
                    <dt><a>TransformBase</a></dt>
                    <dd></dd>
                    <dt><a>TransformStatic</a></dt>
                    <dd></dd>
                    <dt><a>VideoBaseTexture</a></dt>
                    <dd></dd>
                    <dt><a>WebGLExtract</a></dt>
                    <dd></dd>
                    <dt><a>WebGLManager</a></dt>
                    <dd></dd>
                    <dt><a>WebGLPrepare</a></dt>
                    <dd></dd>
                    <dt><a>WebGLRenderer</a></dt>
                    <dd></dd>
                    <dt><a>WebGLState</a></dt>
                    <dd></dd>
                </dl>

### Mixins

<dl>
                    <dt><a>accessibleTarget</a></dt>
                    <dd></dd>
                </dl>

### Namespaces

<dl>
                    <dt><a>CanvasTinter</a></dt>
                    <dd></dd>
                    <dt><a>GroupD8</a></dt>
                    <dd></dd>
                    <dt><a>ticker</a></dt>
                    <dd></dd>
                    <dt><a>utils</a></dt>
                    <dd></dd>
                </dl>

### Members

#### (static, constant) BLEND_MODES :object



##### Type:

* object

##### Properties:

| Name | Type | Description |
| --- | --- | --- |
| `NORMAL` | number |  |
| `ADD` | number |  |
| `MULTIPLY` | number |  |
| `SCREEN` | number |  |
| `OVERLAY` | number |  |
| `DARKEN` | number |  |
| `LIGHTEN` | number |  |
| `COLOR_DODGE` | number |  |
| `COLOR_BURN` | number |  |
| `HARD_LIGHT` | number |  |
| `SOFT_LIGHT` | number |  |
| `DIFFERENCE` | number |  |
| `EXCLUSION` | number |  |
| `HUE` | number |  |
| `SATURATION` | number |  |
| `COLOR` | number |  |
| `LUMINOSITY` | number |  |

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7411</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static, constant) DATA_URI :RegExp|string



##### Type:

* RegExp |string

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7623</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Example

```
`data:image/png;base64`
```

#### (static, constant) DEFAULT_RENDER_OPTIONS :object



##### Type:

* object

##### Properties:

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| `view` | HTMLCanvasElement | null |  |
| `resolution` | number | 1 |  |
| `antialias` | boolean | false |  |
| `forceFXAA` | boolean | false |  |
| `autoResize` | boolean | false |  |
| `transparent` | boolean | false |  |
| `backgroundColor` | number | 0x000000 |  |
| `clearBeforeRender` | boolean | true |  |
| `preserveDrawingBuffer` | boolean | false |  |
| `roundPixels` | boolean | false |  |

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7589</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static, constant) DEG_TO_RAD :number



##### Type:

* number

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7353</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static, constant) DRAW_MODES :object



##### Type:

* object

##### Properties:

| Name | Type | Description |
| --- | --- | --- |
| `POINTS` | number |  |
| `LINES` | number |  |
| `LINE_LOOP` | number |  |
| `LINE_STRIP` | number |  |
| `TRIANGLES` | number |  |
| `TRIANGLE_STRIP` | number |  |
| `TRIANGLE_FAN` | number |  |

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7447</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static, constant) GC_MODES :object



##### Type:

* object

##### Properties:

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| `DEFAULT` | number | MANUAL |  |
| `AUTO` | number |  | Garbage collection will happen periodically automatically |
| `MANUAL` | number |  | Garbage collection will need to be called manually |

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7523</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static) loader



##### Properties:

| Type | Description |
| --- | --- |
| [PIXI.loaders.Loader](PIXI.loaders.Loader.html) |  |

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 35289</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static, constant) MIPMAP_TEXTURES :boolean



##### Type:

* boolean

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7538</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static, constant) PI_2 :number



##### Type:

* number

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7333</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static, constant) PRECISION :object



##### Type:

* object

##### Properties:

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| `DEFAULT` | number |  'mediump' |  |
| `LOW` | number |  'lowp' |  |
| `MEDIUM` | number |  'mediump' |  |
| `HIGH` | number |  'highp' |  |

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7669</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static, constant) RAD_TO_DEG :number



##### Type:

* number

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7343</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static, constant) RENDERER_TYPE :object



##### Type:

* object

##### Properties:

| Name | Type | Description |
| --- | --- | --- |
| `UNKNOWN` | number | Unknown render type. |
| `WEBGL` | number | WebGL render type. |
| `CANVAS` | number | Canvas render type. |

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7377</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static, constant) RESOLUTION :number



##### Type:

* number

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7559</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static, constant) RETINA_PREFIX :RegExp|string



##### Type:

* RegExp |string

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7549</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Example

```
`@2x`
```

#### (static, constant) SCALE_MODES :object



##### Type:

* object

##### Properties:

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| `DEFAULT` | number | LINEAR |  |
| `LINEAR` | number |  | Smooth scaling |
| `NEAREST` | number |  | Pixelating scaling |

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7471</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static, constant) SHAPES :object



##### Type:

* object

##### Properties:

| Name | Type | Description |
| --- | --- | --- |
| `POLY` | number |  |
| `RECT` | number |  |
| `CIRC` | number |  |
| `ELIP` | number |  |
| `RREC` | number |  |

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7649</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static, constant) SPRITE_BATCH_SIZE :number



##### Type:

* number

<dl>
                <dt>Default Value:</dt>
                <dd>
                    <ul>
                        <li>4096</li>
                    </ul>
                </dd>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7722</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static, constant) SPRITE_MAX_TEXTURES :number



##### Type:

* number

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7732</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static, constant) SVG_SIZE :RegExp|string



##### Type:

* RegExp |string

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7634</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Example

```
`<svg width="100" height="100"></svg>`
```

#### (static, constant) TARGET_FPMS :number



##### Type:

* number

<dl>
                <dt>Default Value:</dt>
                <dd>
                    <ul>
                        <li>0.06</li>
                    </ul>
                </dd>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7364</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static, constant) TEXT_GRADIENT :object



##### Type:

* object

##### Properties:

| Name | Type | Description |
| --- | --- | --- |
| `LINEAR_VERTICAL` | number |  |
| `LINEAR_HORIZONTAL` | number |  |

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7703</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static, constant) TRANSFORM_MODE :object



##### Type:

* object

##### Properties:

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| `DEFAULT` | number | STATIC |  |
| `STATIC` | number |  |  |
| `DYNAMIC` | number |  |  |

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7687</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static, constant) URL_FILE_EXTENSION :RegExp|string



##### Type:

* RegExp |string

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7611</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Example

```
`image.png`
```

#### (static, constant) VERSION :string



##### Type:

* string

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7323</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### (static, constant) WRAP_MODES :object



##### Type:

* object

##### Properties:

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| `DEFAULT` | number | CLAMP |  |
| `CLAMP` | number |  | The textures uvs are clamped |
| `REPEAT` | number |  | The texture uvs tile and repeat |
| `MIRRORED_REPEAT` | number |  | The texture uvs tile and repeat with mirroring |

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 7496</a>
                        </li>
                    </ul>
                </dd>
            </dl>

### Methods

#### (static) autoDetectRenderer (width opt, height opt, options opt, noWebGL opt) → {[PIXI.WebGLRenderer](PIXI.WebGLRenderer.html)|[PIXI.CanvasRenderer](PIXI.CanvasRenderer.html)}



##### Parameters:

<table>
                <thead>
                    <tr>
                        <th>Name</th>
                        <th>Type</th>
                        <th>Attributes</th>
                        <th>Default</th>
                        <th>Description</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><code>width</code></td>
                        <td>
                            <span>number</span>
                        </td>
                        <td> &lt;optional&gt;<br>
                        </td>
                        <td> 800 </td>
                        <td>the width of the renderers view</td>
                    </tr>
                    <tr>
                        <td><code>height</code></td>
                        <td>
                            <span>number</span>
                        </td>
                        <td> &lt;optional&gt;<br>
                        </td>
                        <td> 600 </td>
                        <td>the height of the renderers view</td>
                    </tr>
                    <tr>
                        <td><code>options</code></td>
                        <td>
                            <span>object</span>
                        </td>
                        <td> &lt;optional&gt;<br>
                        </td>
                        <td>
                        </td>
                        <td>The optional renderer parameters <h6>Properties</h6>
                            <table>
                                <thead>
                                    <tr>
                                        <th>Name</th>
                                        <th>Type</th>
                                        <th>Attributes</th>
                                        <th>Default</th>
                                        <th>Description</th>
                                    </tr>
                                </thead>
                                <tbody>
                                    <tr>
                                        <td><code>view</code></td>
                                        <td>
                                            <span>HTMLCanvasElement</span>
                                        </td>
                                        <td> &lt;optional&gt;<br>
                                        </td>
                                        <td>
                                        </td>
                                        <td>the canvas to use as a view, optional</td>
                                    </tr>
                                    <tr>
                                        <td><code>transparent</code></td>
                                        <td>
                                            <span>boolean</span>
                                        </td>
                                        <td> &lt;optional&gt;<br>
                                        </td>
                                        <td> false </td>
                                        <td>If the render view is transparent, default false</td>
                                    </tr>
                                    <tr>
                                        <td><code>antialias</code></td>
                                        <td>
                                            <span>boolean</span>
                                        </td>
                                        <td> &lt;optional&gt;<br>
                                        </td>
                                        <td> false </td>
                                        <td>sets antialias (only applicable in chrome at the moment)</td>
                                    </tr>
                                    <tr>
                                        <td><code>preserveDrawingBuffer</code></td>
                                        <td>
                                            <span>boolean</span>
                                        </td>
                                        <td> &lt;optional&gt;<br>
                                        </td>
                                        <td> false </td>
                                        <td>enables drawing buffer preservation, enable this if you need to call toDataUrl on the webgl context</td>
                                    </tr>
                                    <tr>
                                        <td><code>resolution</code></td>
                                        <td>
                                            <span>number</span>
                                        </td>
                                        <td> &lt;optional&gt;<br>
                                        </td>
                                        <td> 1 </td>
                                        <td>The resolution / device pixel ratio of the renderer, retina would be 2</td>
                                    </tr>
                                </tbody>
                            </table>
                        </td>
                    </tr>
                    <tr>
                        <td><code>noWebGL</code></td>
                        <td>
                            <span>boolean</span>
                        </td>
                        <td> &lt;optional&gt;<br>
                        </td>
                        <td> false </td>
                        <td>prevents selection of WebGL renderer, even if such is present</td>
                    </tr>
                </tbody>
            </table>
<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 12865</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:


<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>PIXI.WebGLRenderer</a></span> | <span><a>PIXI.CanvasRenderer</a></span>
                </dd>
            </dl>

#### (static) mapCanvasBlendModesToPixi (array opt) → {[Array](Array.html).<string>}



##### Parameters:

| Name | Type | Attributes | Default | Description |
| --- | --- | --- | --- | --- |
| `array` | [Array](Array.html).<string> | <optional> | [] | The array to output into. |

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 15647</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:


<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;string&gt;</span>
                </dd>
            </dl>

#### (static) mapWebGLBlendModesToPixi (gl, array opt) → {[Array](Array.html).<string>}



##### Parameters:

| Name | Type | Attributes | Default | Description |
| --- | --- | --- | --- | --- |
| `gl` | WebGLRenderingContext |  |  | The rendering context. |
| `array` | [Array](Array.html).<string> | <optional> | [] | The array to output into. |

<dl>
                <dt>Source:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>libs/pixi.js</a>, <a>line 18909</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:


<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;string&gt;</span>
                </dd>
            </dl>

## [Home](index.html)

### Classes

* [Bitmap](Bitmap.html)
* [CacheEntry](CacheEntry.html)
* [CacheMap](CacheMap.html)
* [Graphics](Graphics.html)
* [Html5Audio](Html5Audio.html)
* [Input](Input.html)
* [JsExtensions](JsExtensions.html)
* [JsonEx](JsonEx.html)
* [AccessibilityManager](PIXI.AccessibilityManager.html)
* [BaseRenderTexture](PIXI.BaseRenderTexture.html)
* [BaseTexture](PIXI.BaseTexture.html)
* [Bounds](PIXI.Bounds.html)
* [CanvasExtract](PIXI.CanvasExtract.html)
* [CanvasMaskManager](PIXI.CanvasMaskManager.html)
* [CanvasPrepare](PIXI.CanvasPrepare.html)
* [CanvasRenderer](PIXI.CanvasRenderer.html)
* [CanvasRenderTarget](PIXI.CanvasRenderTarget.html)
* [Circle](PIXI.Circle.html)
* [Container](PIXI.Container.html)
* [createIndicesForQuads](PIXI.createIndicesForQuads.html)
* [DisplayObject](PIXI.DisplayObject.html)
* [Ellipse](PIXI.Ellipse.html)
* [BitmapText](PIXI.extras.BitmapText.html)
* [HardLightShader](PIXI.extras.HardLightShader.html)
* [mapFilterBlendModesToPixi](PIXI.extras.mapFilterBlendModesToPixi.html)
* [MovieClip](PIXI.extras.MovieClip.html)
* [NormalShader](PIXI.extras.NormalShader.html)
* [OverlayShader](PIXI.extras.OverlayShader.html)
* [PictureRenderer](PIXI.extras.PictureRenderer.html)
* [PictureShader](PIXI.extras.PictureShader.html)
* [PictureSprite](PIXI.extras.PictureSprite.html)
* [PictureTilingSprite](PIXI.extras.PictureTilingSprite.html)
* [TilingSprite](PIXI.extras.TilingSprite.html)
* [Filter](PIXI.Filter.html)
* [FilterManager](PIXI.FilterManager.html)
* [BlurFilter](PIXI.filters.BlurFilter.html)
* [BlurXFilter](PIXI.filters.BlurXFilter.html)
* [BlurYFilter](PIXI.filters.BlurYFilter.html)
* [ColorMatrixFilter](PIXI.filters.ColorMatrixFilter.html)
* [DisplacementFilter](PIXI.filters.DisplacementFilter.html)
* [NoiseFilter](PIXI.filters.NoiseFilter.html)
* [VoidFilter](PIXI.filters.VoidFilter.html)
* [FXAAFilter](PIXI.FXAAFilter.html)
* [Buffer](PIXI.glCore.Buffer.html)
* [createContext](PIXI.glCore.createContext.html)
* [Framebuffer](PIXI.glCore.Framebuffer.html)
* [Shader](PIXI.glCore.Shader.html)
* [compileProgram](PIXI.glCore.shader.compileProgram.html)
* [defaultValue](PIXI.glCore.shader.defaultValue.html)
* [extractAttributes](PIXI.glCore.shader.extractAttributes.html)
* [extractUniforms](PIXI.glCore.shader.extractUniforms.html)
* [generateUniformAccessObject](PIXI.glCore.shader.generateUniformAccessObject.html)
* [mapSize](PIXI.glCore.shader.mapSize.html)
* [Texture](PIXI.glCore.Texture.html)
* [VertexArrayObject](PIXI.glCore.VertexArrayObject.html)
* [Graphics](PIXI.Graphics.html)
* [GraphicsData](PIXI.GraphicsData.html)
* [GraphicsRenderer](PIXI.GraphicsRenderer.html)
* [InteractionData](PIXI.interaction.InteractionData.html)
* [InteractionEvent](PIXI.interaction.InteractionEvent.html)
* [InteractionManager](PIXI.interaction.InteractionManager.html)
* [Loader](PIXI.loaders.Loader.html)
* [mapWebGLDrawModesToPixi](PIXI.mapWebGLDrawModesToPixi.html)
* [MaskManager](PIXI.MaskManager.html)
* [Matrix](PIXI.Matrix.html)
* [Mesh](PIXI.mesh.Mesh.html)
* [NineSlicePlane](PIXI.mesh.NineSlicePlane.html)
* [Plane](PIXI.mesh.Plane.html)
* [Rope](PIXI.mesh.Rope.html)
* [ObjectRenderer](PIXI.ObjectRenderer.html)
* [ObservablePoint](PIXI.ObservablePoint.html)
* [ParticleContainer](PIXI.particles.ParticleContainer.html)
* [ParticleShader](PIXI.ParticleShader.html)
* [Point](PIXI.Point.html)
* [Polygon](PIXI.Polygon.html)
* [PrimitiveShader](PIXI.PrimitiveShader.html)
* [Quad](PIXI.Quad.html)
* [Rectangle](PIXI.Rectangle.html)
* [RenderTarget](PIXI.RenderTarget.html)
* [RenderTexture](PIXI.RenderTexture.html)
* [RoundedRectangle](PIXI.RoundedRectangle.html)
* [Shader](PIXI.Shader.html)
* [Sprite](PIXI.Sprite.html)
* [SpriteMaskFilter](PIXI.SpriteMaskFilter.html)
* [StencilManager](PIXI.StencilManager.html)
* [SystemRenderer](PIXI.SystemRenderer.html)
* [Text](PIXI.Text.html)
* [TextStyle](PIXI.TextStyle.html)
* [Texture](PIXI.Texture.html)
* [TextureGarbageCollector](PIXI.TextureGarbageCollector.html)
* [TextureManager](PIXI.TextureManager.html)
* [Ticker](PIXI.ticker.Ticker.html)
* [Transform](PIXI.Transform.html)
* [TransformBase](PIXI.TransformBase.html)
* [TransformStatic](PIXI.TransformStatic.html)
* [VideoBaseTexture](PIXI.VideoBaseTexture.html)
* [WebGLExtract](PIXI.WebGLExtract.html)
* [WebGLManager](PIXI.WebGLManager.html)
* [WebGLPrepare](PIXI.WebGLPrepare.html)
* [WebGLRenderer](PIXI.WebGLRenderer.html)
* [WebGLState](PIXI.WebGLState.html)
* [Point](Point.html)
* [Rectangle](Rectangle.html)
* [ResourceHandler](ResourceHandler.html)
* [Scene_Base](Scene_Base.html)
* [ScreenSprite](ScreenSprite.html)
* [ShaderTilemap](ShaderTilemap.html)
* [Sprite](Sprite.html)
* [Stage](Stage.html)
* [Tilemap](Tilemap.html)
* [TilingSprite](TilingSprite.html)
* [ToneFilter](ToneFilter.html)
* [ToneSprite](ToneSprite.html)
* [TouchInput](TouchInput.html)
* [Utils](Utils.html)
* [Weather](Weather.html)
* [WebAudio](WebAudio.html)
* [Window](Window.html)
* [WindowLayer](WindowLayer.html)

### Events

* [error](PIXI.BaseRenderTexture.html#event:error)
* [loaded](PIXI.BaseRenderTexture.html#event:loaded)
* [error](PIXI.BaseTexture.html#event:error)
* [loaded](PIXI.BaseTexture.html#event:loaded)
* [click](PIXI.interaction.InteractionManager.html#event:click)
* [mousedown](PIXI.interaction.InteractionManager.html#event:mousedown)
* [mousemove](PIXI.interaction.InteractionManager.html#event:mousemove)
* [mouseout](PIXI.interaction.InteractionManager.html#event:mouseout)
* [mouseover](PIXI.interaction.InteractionManager.html#event:mouseover)
* [mouseup](PIXI.interaction.InteractionManager.html#event:mouseup)
* [mouseupoutside](PIXI.interaction.InteractionManager.html#event:mouseupoutside)
* [pointerdown](PIXI.interaction.InteractionManager.html#event:pointerdown)
* [pointermove](PIXI.interaction.InteractionManager.html#event:pointermove)
* [pointerout](PIXI.interaction.InteractionManager.html#event:pointerout)
* [pointerover](PIXI.interaction.InteractionManager.html#event:pointerover)
* [pointertap](PIXI.interaction.InteractionManager.html#event:pointertap)
* [pointerup](PIXI.interaction.InteractionManager.html#event:pointerup)
* [pointerupoutside](PIXI.interaction.InteractionManager.html#event:pointerupoutside)
* [rightclick](PIXI.interaction.InteractionManager.html#event:rightclick)
* [rightdown](PIXI.interaction.InteractionManager.html#event:rightdown)
* [rightup](PIXI.interaction.InteractionManager.html#event:rightup)
* [rightupoutside](PIXI.interaction.InteractionManager.html#event:rightupoutside)
* [tap](PIXI.interaction.InteractionManager.html#event:tap)
* [touchend](PIXI.interaction.InteractionManager.html#event:touchend)
* [touchendoutside](PIXI.interaction.InteractionManager.html#event:touchendoutside)
* [touchmove](PIXI.interaction.InteractionManager.html#event:touchmove)
* [touchstart](PIXI.interaction.InteractionManager.html#event:touchstart)
* [update](PIXI.RenderTexture.html#event:update)
* [update](PIXI.Texture.html#event:update)
* [error](PIXI.VideoBaseTexture.html#event:error)
* [loaded](PIXI.VideoBaseTexture.html#event:loaded)

### Namespaces

* [PIXI](PIXI.html)
* [CanvasTinter](PIXI.CanvasTinter.html)
* [GroupD8](PIXI.GroupD8.html)
* [ticker](PIXI.ticker.html)
* [utils](PIXI.utils.html)

### Mixins

* [accessibleTarget](PIXI.accessibleTarget.html)
* [interactiveTarget](PIXI.interaction.interactiveTarget.html)
* [pluginTarget](PIXI.utils.pluginTarget.html)

### Global

* [addChild](global.html#addChild)
* [addChildAt](global.html#addChildAt)
* [addChildToBack](global.html#addChildToBack)
* [addLoadListener](global.html#addLoadListener)
* [addStopListener](global.html#addStopListener)
* [adjustHue](global.html#adjustHue)
* [adjustSaturation](global.html#adjustSaturation)
* [adjustTone](global.html#adjustTone)
* [after](global.html#after)
* [before](global.html#before)
* [blt](global.html#blt)
* [blur](global.html#blur)
* [cached](global.html#cached)
* [canPlayM4a](global.html)
* [canPlayOgg](global.html)
* [canPlayVideoType](global.html)
* [canReadGameFiles](global.html)
* [canUseDifferenceBlend](global.html)
* [canUseSaturationBlend](global.html)
* [checkDirty](global.html#checkDirty)
* [clear](global.html)
* [clearRect](global.html#clearRect)
* [drawCircle](global.html#drawCircle)
* [drawSmallText](global.html#drawSmallText)
* [drawText](global.html#drawText)
* [endLoading](global.html)
* [enqueue](global.html#enqueue)
* [eraseLoadingError](global.html)
* [fadeIn](global.html)
* [fadeOut](global.html)
* [fillAll](global.html#fillAll)
* [fillRect](global.html#fillRect)
* [getAlphaPixel](global.html#getAlphaPixel)
* [getBlendColor](global.html#getBlendColor)
* [getColorTone](global.html#getColorTone)
* [getPixel](global.html#getPixel)
* [gradientFillRect](global.html#gradientFillRect)
* [hasWebGL](global.html)
* [hideFps](global.html)
* [initialize](global.html)
* [isAndroidChrome](global.html)
* [isCancelled](global.html)
* [isClosed](global.html#isClosed)
* [isError](global.html#isError)
* [isFontLoaded](global.html)
* [isInsideCanvas](global.html)
* [isLongPressed](global.html)
* [isMobileDevice](global.html)
* [isMobileSafari](global.html)
* [isMoved](global.html)
* [isNwjs](global.html)
* [isOpen](global.html#isOpen)
* [isOptionValid](global.html)
* [isPlaying](global.html#isPlaying)
* [isPressed](global.html)
* [isReady](global.html#isReady)
* [isReleased](global.html)
* [isRepeated](global.html)
* [isSupportPassiveEvent](global.html)
* [isTriggered](global.html)
* [isVideoPlaying](global.html)
* [isWebGL](global.html)
* [load](global.html)
* [loadFont](global.html)
* [makeDeepCopy](global.html)
* [measureTextWidth](global.html#measureTextWidth)
* [move](global.html#move)
* [pageToCanvasX](global.html)
* [pageToCanvasY](global.html)
* [parse](global.html)
* [play](global.html)
* [playVideo](global.html)
* [printError](global.html)
* [printLoadingError](global.html)
* [printStackTrace](global.html)
* [punycode](global.html#punycode)
* [refresh](global.html#refresh)
* [removeChild](global.html#removeChild)
* [removeChildAt](global.html#removeChildAt)
* [render](global.html)
* [renderCanvas](global.html#renderCanvas)
* [renderWebGL](global.html#renderWebGL)
* [reset](global.html#reset)
* [resize](global.html#resize)
* [rgbToCssColor](global.html)
* [rotateHue](global.html#rotateHue)
* [seek](global.html)
* [set](global.html#set)
* [setBlack](global.html#setBlack)
* [setBlendColor](global.html#setBlendColor)
* [setColor](global.html#setColor)
* [setColorTone](global.html#setColorTone)
* [setCursorRect](global.html#setCursorRect)
* [setData](global.html#setData)
* [setEnableProgress](global.html)
* [setErrorMessage](global.html)
* [setFrame](global.html#setFrame)
* [setLoadingImage](global.html)
* [setMasterVolume](global.html)
* [setTone](global.html#setTone)
* [setup](global.html)
* [setVideoVolume](global.html)
* [setWhite](global.html#setWhite)
* [showFps](global.html)
* [snap](global.html)
* [startLoading](global.html)
* [stop](global.html#stop)
* [stringify](global.html)
* [the](global.html#the)
* [The](global.html#The)
* [tickEnd](global.html)
* [tickStart](global.html)
* [touch](global.html#touch)
* [update](global.html#update)
* [updateBitmaps](global.html#updateBitmaps)
* [updateLoading](global.html)
* [whether](global.html#whether)

 <br>

  Documentation generated by [JSDoc 3.5.5](https://github.com/jsdoc3/jsdoc)