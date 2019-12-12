# Gruppenfoto optimieren

Purpose of this project is to create software which merges photographs of groups to ensure as many subjects as possible look directly at the camera with open eyes and a smile.

To achieve this the application has to:

* recognize faces
* evaluate faces according to a number of fixed criteria
  * person is smiling
  * eyes are open
  * looking at the camera
  * face is not obstructed
  * ...
* respect which face belongs to whose head and body
* pick the optimal picture of each persons face from all sources
* merge several pictures into one
  * compensate for small movements of both people and the camera to avoid artifacts

## Team members

* Tobias Bossert
* Kersten Coldewey
* David Neugebauer

## Milestones

1. detecting faces ✔️
2. landmark detection ✔️
3. face swap ✔️
4. seperating the face from the background cleanly
  * calculating average skin color
  * build a mask / outline
5. evaluation of smile and eyes
  * aspect ratio of the eyes
6. identifiying the same people in multiple photos, picking the best face ✔️
7. merging
