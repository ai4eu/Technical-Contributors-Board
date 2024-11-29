# Agenda
1. A concept to synchronize the (old) community portal contents into the AIoD metadata-service (Alexandros Tzoumas)
2. The new AIoD MyLibrary UI that could include the contents from above (Pedro Lopes)
3. Feedback, Discussion and Questions



# Minutes
* The "old" Drupal community portal has maintenance issues that could lead to problems and needs a migration plan.
* There is a synchronizer being implemented that would map community portal content into the metadata service
* the content of the old portal can not yet be mapped completely into the metadata service. Especially the binary documnets (PDF or Word files and images) that have been stored directly in the Drupal database need a migration concept, because the metadata service obviously does not store binary contents.
* There were two ideas how this could happen:
  * migrate the binary contents to zenodo and include only the links in the metadata
  * migrate the contents from the Drupal database to the "new" wordpress system
* To migrate, we need the consent of the providers, and there is a now consent dialog beein presented to Drupal users at login
* How do we handle content of inactive users, even after a mailing campaingn?
* We need to take into account the conceptual model
* The new MyLibrary App will act as a frontend for the metadata service including a way to add content
* Shall we switch the old Drupal system to read-only mode at some point in time, or even turn it off? 

