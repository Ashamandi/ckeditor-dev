@bender-tags: embed, 14570, tc, 4.5.10
@bender-ui: collapsed
@bender-ckeditor-plugins: embed,image2,wysiwygarea,sourcearea,htmlwriter,entities,toolbar,elementspath,undo,clipboard

**Procedure:**

1. Embed URL from "Test URLs" list between paragraphs inside the editor.
2. Double click on video to open Media Embed dialog
3. Press ESC or click on Cancel button

**Expected:**

"Media Embed" dialog closed & focus goes to the video.

**Unexpected:**

"Media Embed" dialog closed but focus goes to the end of the last paragraph.

Notes:

* Many iframely's iframes throw errors on IEs (8-11) - this isn't our fault. Warnings on other browsers aren't our fault too...
