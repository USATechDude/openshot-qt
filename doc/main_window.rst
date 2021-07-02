.. Copyright (c) 2008-2020 OpenShot Studios, LLC
 (http://www.openshotstudios.com). This file is part of
 OpenShot Video Editor (http://www.openshot.org), an open-source project
 dedicated to delivering high quality video editing and animation solutions
 to the world.

.. OpenShot Video Editor is free software: you can redistribute it and/or modify
 it under the terms of the GNU General Public License as published by
 the Free Software Foundation, either version 3 of the License, or
 (at your option) any later version.

.. OpenShot Video Editor is distributed in the hope that it will be useful,
 but WITHOUT ANY WARRANTY; without even the implied warranty of
 MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 GNU General Public License for more details.

.. You should have received a copy of the GNU General Public License
 along with OpenShot Library.  If not, see <http://www.gnu.org/licenses/>.

Main Window
===========

OpenShot Video Editor has one main window which contains most of the information, buttons,
and menus needed to edit your video project.

Overview
--------

.. image:: images/main-window.jpg

.. table::
     :widths: 5 22 73

     ==  ==================  ============
     #   Name                Description
     ==  ==================  ============
     1   Main Toolbar        Contains buttons to open, save, and export your video project.
     2   Function Tabs       Switch between Project Files, Transitions, and Effects.
     3   Project Files       All audio, video, and image files that have been imported into your project.
     4   Preview Window      This is the area that the video will playback on the screen.
     5   Edit Toolbar        This toolbar contains buttons used for snapping, inserting markers, and jumping between markers.
     6   Zoom Slider         This slider will adjust the time-scale of your timeline.
     7   Play-head / Ruler   The ruler shows the time-scale, and the red line is the play-head. The play-head represents the current playback position.
     8   Timeline            The timeline visualizes your video project, and each clip and transition in your project.
     9   Filter              Filter the list of items shown (project files, transitions, and effects) by using these buttons and filter textbox. Enter a few letters of what you are looking for, and the results will be shown.
     ==  ==================  ============

For step-by-step instructions on the basic usage of OpenShot, be sure to read the
:ref:`quick_tutorial_ref`.

Built-in Tutorial
-----------------
When you first launch OpenShot, you will be presented with a friendly built-in tutorial. It will demonstrate and explain
the basics. Clicking :guilabel:`Next` will jump to the next topic. You can always view this tutorial again from the :menuselection:`Help --> Tutorial` menu.

.. image:: images/built-in-tutorial.jpg

.. _tracks-layers_ref:

Tracks
------

OpenShot uses tracks to layer videos and images. The top most track is the top
layer, and the bottom track is the bottom layer. If you are familiar with layers
in a photo editing application, then you should be quite familiar with this
concept. OpenShot will stack the layers and mix each one together, just like a
photo editing application. You can have an unlimited number of tracks, but
typically a video project will not need more than 10 tracks.

Here's a typical three-track video project, for example:

.. image:: images/tracks.jpg

.. table::
     :widths: 5 22 73

     ==  ==================  ============
     #   Track               Description
     ==  ==================  ============
     1   Top Track           Clips that will always be visible in front of other clips
     2   Middle Track        Clips in the middle (might or might not be visible, depending on what is above them)
     3   Bottom Track        Clips that will always be hidden behind anything on the tracks above
     ==  ==================  ============

.. _keyboard_shortcut_ref:

Keyboard Shortcuts
------------------
Here is a list of the default keyboard shortcuts supported by OpenShot. You can
configure these shortcuts in the Preferences window, which is opened by selecting
:menuselection:`Edit --> Preferences` from the OpenShot menu bar.
(On macOS, choose :menuselection:`OpenShot Video Editor --> Preferences`.)
Learning a few of these shortcuts can save you a bunch of time!

.. list-table::
   :header-rows: 1
   :widths: 15 20

   * - Action 
     - Shortcut 
   * - About OpenShot 
     - :kbd:`Ctrl` + :kbd:`H` 
   * - Add Marker 
     - :kbd:`Ctrl` + :kbd:`M` 
   * - Add Track 
     - :kbd:`Ctrl` + :kbd:`Shift` + :kbd:`T` 
   * - Add to Timeline 
     - :kbd:`Ctrl` + :kbd:`W` 
   * - Animated Title 
     - :kbd:`Ctrl` + :kbd:`B` 
   * - Center on Playhead 
     - :kbd:`Ctrl` + :kbd:`Up` 
   * - Choose Profile 
     - :kbd:`Ctrl` + :kbd:`P` 
   * - Copy 
     - :kbd:`Ctrl` + :kbd:`C` 
   * - Delete Item 
     - :kbd:`Delete` 
   * - Delete Item 
     - :kbd:`Backspace` 
   * - Details View 
     - :kbd:`Ctrl` + :kbd:`D` 
   * - Duplicate Title 
     - :kbd:`Ctrl` + :kbd:`Shift` + :kbd:`C` 
   * - Export Video 
     - :kbd:`Ctrl` + :kbd:`E` 
   * - Fast Forward 
     - :kbd:`L` 
   * - Fullscreen 
     - :kbd:`F11` 
   * - Import Files 
     - :kbd:`Ctrl` + :kbd:`F` 
   * - Insert Keyframe 
     - :kbd:`Ctrl` + :kbd:`Shift` + :kbd:`E` 
   * - Jump to End 
     - :kbd:`Ctrl` + :kbd:`End` 
   * - Jump to Start 
     - :kbd:`Ctrl` + :kbd:`Home` 
   * - New Project 
     - :kbd:`Ctrl` + :kbd:`N` 
   * - Next Frame 
     - :kbd:`Right` 
   * - Next Marker 
     - :kbd:`Ctrl` + :kbd:`Right` 
   * - Open Project 
     - :kbd:`Ctrl` + :kbd:`O` 
   * - Paste 
     - :kbd:`Ctrl` + :kbd:`V` 
   * - Play/Pause Toggle 
     - :kbd:`Space` 
   * - Play/Pause Toggle 
     - :kbd:`Up` 
   * - Play/Pause Toggle 
     - :kbd:`Down` 
   * - Play/Pause Toggle 
     - :kbd:`K` 
   * - Preferences 
     - :kbd:`Ctrl` + :kbd:`Shift` + :kbd:`P` 
   * - Previous Frame 
     - :kbd:`Left` 
   * - Previous Marker 
     - :kbd:`Ctrl` + :kbd:`Left` 
   * - Properties 
     - :kbd:`Ctrl` + :kbd:`I` 
   * - Quit 
     - :kbd:`Ctrl` + :kbd:`Q` 
   * - Redo 
     - :kbd:`Ctrl` + :kbd:`Y` 
   * - Rewind 
     - :kbd:`J` 
   * - Save Project 
     - :kbd:`Ctrl` + :kbd:`S` 
   * - Save Project As... 
     - :kbd:`Ctrl` + :kbd:`Shift` + :kbd:`S` 
   * - Scroll Timeline 
     - :kbd:`Alt` + Middle Mouse Button 
   * - Select All 
     - :kbd:`Ctrl` + :kbd:`A` 
   * - Select None 
     - :kbd:`Ctrl` + :kbd:`Shift` + :kbd:`A` 
   * - Slice All: Keep Both Sides 
     - :kbd:`Ctrl` + :kbd:`K` 
   * - Slice All: Keep Left Side 
     - :kbd:`Ctrl` + :kbd:`L` 
   * - Slice All: Keep Right Side 
     - :kbd:`Ctrl` + :kbd:`J` 
   * - Slice Selected: Keep Both Sides 
     - :kbd:`Ctrl` + :kbd:`s` 
   * - Slice Selected: Keep Left Side 
     - :kbd:`Ctrl` + :kbd:`d` 
   * - Slice Selected: Keep Right Side 
     - :kbd:`Ctrl` + :kbd:`a` 
   * - Toggle Snapping 
     - :kbd:`Ctrl` + :kbd:`G` 
   * - Split Clip 
     - :kbd:`Ctrl` + :kbd:`X` 
   * - Thumbnail View 
     - :kbd:`Ctrl` + :kbd:`Shift` + :kbd:`D` 
   * - Title Editor 
     - :kbd:`Ctrl` + :kbd:`T` 
   * - Toggle Editor 
     - :kbd:`Ctrl` + :kbd:`R` 
   * - Undo 
     - :kbd:`Ctrl` + :kbd:`Z` 
   * - Zoom In 
     - :kbd:`=` 
   * - Zoom Out 
     - :kbd:`-` 
   * - Zoom In / Out 
     - :kbd:`Ctrl` + Middle Mouse Button
