# Mobile Friendly Version of Date Range Picker for Bootstrap

This is a fork of version 2.1.12 of [Date Range Picker for Bootstrap](https://github.com/dangrossman/bootstrap-daterangepicker).

It was created because Date Range Picker for Bootstrap at the time of writing does not handle input of date ranges on mobile devices well. The problem is that for ranges it always shows 2 calendars. These do not fit on the small screen, which looks odd and forces the user to scroll in order to enter a range.

This fork adds this to version 2.1.12:

1) Fixes a bug where the dropdown drifts away from the input element when the user resizes the screen or reorients their mobile while the dropdown is open. This bug has now been fixed in later versions of Date Range Picker for Bootstrap.

2) Introduces a new option useHtml5Calendar. See below.

## useHtml5Calendar (default: false)

When true:
* The calendars are not shown in the dropdown;
* The two input boxes for the start and end dates are of type "date" instead of "text". When the user taps a date input, the mobile browser presents a user friendly calendar control.

This is not an ideal solution. For example, the date inputs do not support min date, max date, etc. But for now it is better than nothing.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
