# Arquitectura de triangulación invertida para el mantenimiento de framework de gestión de plantillas css [(referencia)][2] [![Build Status](https://travis-ci.org/alegorico/forkfrcss.svg?branch=master)](https://travis-ci.org/alegorico/forkfrcss)

![modelo del triangulo invertido][1]

 ### SETTINGS
 _usado por el preprocesador, contiene: variables, definiciones, etc._
 * Config...............Project-level config.
 * Global...............Project-specific, globally available settings.
 
 ###  TOOLS
 _mixins y funciones._
 * Mixins...............Global mixins.
 
 ###  GENERIC
 _reset y/o normalizadores. Es una capa intermedia de propósito general donde insertamos fracmentos de terceros, aqui ya tendriamos disponible los tools y setting para su uso._
 * Normalize.css........Normalise browser defaults…
 * Reset................…and zero them out.
 * Box-sizing...........More manageable box-model.
 * Shared...............Share certain high-level styles as broadly as possible.
 
 ###  ELEMENTS
 _definen los bloques centrales. de forma general_
 * Headings.............H1–H6
 * Forms................Element-level form styling.
 
 ###  OBJECTS
 _aquí se definen los elementos genericos no pertenecientes a la capa anterior y de manera abstracta._
 * Layout...............Simple Layout abstraction tool.
 * List-bare............‘Unstyled’ lists: bullets and indent removed.
 * List-pair............Simple key–value pair list.
 * Pack.................Force elements to pack up into all available space.
 
 ###  COMPONENTS
 _incluye los fragmentos y componentes mas especificos._
 * Forms................Component-level form styling.
 * Buttons..............Element-agnostic button styles.
 * Comments.............Comment styles.
 * Messaging............User feedback messaging.
 
 ###  TRUMPS
 _utilidades y helpers mas especializados._
 * Typography...........Utilities for manipulating text.
 * Display..............Helper classes for showing or hiding content.
 * Widths...............Width helper classes for use with our Layout system.

---

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

[1]:https://www.xfivecdn.com/xfive/wp-content/uploads/2016/02/01083650/itcss-layers2.svg
[2]:https://www.xfive.co/blog/itcss-scalable-maintainable-css-architecture/
