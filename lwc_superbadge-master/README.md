# Salesforce DX Project: Next Steps

Now that you’ve created a Salesforce DX project, what’s next? Here are some documentation resources to get you started.

Pronto para enfrentar este Superbadge?
Você fará o trabalho para este superbadge em sua própria organização prática. Cada superbadge tem requisitos de organização, configurações, licenças e restrições únicas. Para configurar uma nova organização para este superbadge, siga cuidadosamente as etapas na seção Trabalho preparatório e notas; este processo pode envolver a instalação de um pacote em um novo Trailhead Playground ou a inscrição em uma organização Developer Edition especial.

Para criar um novo Trailhead Playground agora, clique em Lançar. Para criar uma organização Developer Edition especial, siga as etapas na seção Trabalho preparatório e notas.


Curious Badger Playground
Última utilização em 17/06/2022
Complete each challenge to earn your superbadge
1 Quiz: Credential Security
Answer questions about superbadge credentials and the Trailhead Credential and Certification Program. Please review the Superbadge Challenge Help article for information about the Salesforce Certification Program information and Superbadge Code of Conduct.

2 Before you start
Complete all of the prework, including the installation of the unlocked package. Once you click the button, this step will also pre-populate the boat data in your playground.
Before you begin the challenges, review the Lightning Web Components Specialist: Trailhead Challenge Help knowledge article. Also, read the requirements and the scenario entirely. They are presented in a certain order, to simulate a real-life situation, and you have to identify the dependencies between the components. We recommend developing the components in the order that the challenges are checked.
Since Lightning Web Components use a case-sensitive language, make sure you are applying the correct case in your code.


3 Build the Boat Message Service channel
In order to create communication across the DOM, you will need to create a Lightning Message Service channel. Deploy the BoatMessageChannel to your org so you can reference it in your components.


4 Get BoatDataService class ready for action
Make the proper adjustments to the Apex class BoatDataService so you can reference its methods within the Lightning web components. Remember not to add comments or any other content between annotations and the methods declarations.

5 Build the component boatSearchForm
Build the boatSearchForm to let the users filter results by boat type.

6 Build the component boatTile
Create the boat tiles, to display a boat for rent. This tile reacts to a click event to set the currently selected boat.

7 Customize the component boatMap
Customize the component boatMap that was included in the unlocked package that you installed in your playground as part of the pre-work for this superbadge.

8 Build the component boatsNearMe and display boats near you
Create the component boatsNearMe and show boats that are near the user, using the browser location and boat type. Display them on a map, always with the consent of the user (and only while the page is open).

9 Build the component boatSearchResults
Create the component boatSearchResults to show the search results in the Gallery, Boat Editor, and Boats Near Me tabs.

10 Build the component boatSearch
Build the boatSearch, a container component that invokes both boatSearchForm and boatSearchResults.
Do not forget to add the loading spinner and a button so the users can create a new boat record.

11 Integrate Third Party Scripts to build the component fiveStarRating
Create a fiveStarRating component to enable associates to give the boats a rating from 1–5 stars. Give the component edit and read-only modes that are used in the form and output, respectively.

12 Add Reviews to the boats with the component boatAddReviewForm
Create the component boatAddReviewForm so users can create reviews of the boats. Instantiate an addBoatReview component inside the Add Review tab and display the form. When a user clicks Submit, save the record and switch the active tab to Reviews.

13 Display the boat reviews with the component boatReviews
Inside the Reviews tab, invoke a boatReviews component that outputs the boat reviews, as shown in the business requirements. Hyperlink the name of the user to their record in Salesforce when possible.

14 Display boat details and reviews with boatDetailTabs
Add the components boatReviews and boatAddReviewForm to boatDetailTabs and show details about the currently selected boat.

15 Build a solution using Lightning Web Components to display Similar Boats
Analyze an existing Visualforce page and Visualforce components to create a solution that leverages many cool new features present in Lightning Web Components to display similar boats.

16 Build the Friend Ships Lightning Page with all the components
Now that you have created the previous components, create a Lightning page to display the boatSearch, boatDetailTabs, and boatMap in a layout that follows all the presented requirements.

17 Build the Boat Record Page with the location of the boat and Similar Boats
Now that you have developed the similarBoats component, make the adjustments to empower Admins to configure the Boat record page and display similar boats by Type, Length, and Price.

18 Lightning Web Components - Quiz
Answer questions about Lightning Web Components, debugging, general implementation, and more.

19 Unit Tests - Quiz
Answer questions about Jest tests, Shadow Dom elements, Apex Wire adapters, and more.
## How Do You Plan to Deploy Your Changes?

Do you want to deploy a set of changes, or create a self-contained application? Choose a [development model](https://developer.salesforce.com/tools/vscode/en/user-guide/development-models).

## Configure Your Salesforce DX Project

The `sfdx-project.json` file contains useful configuration information for your project. See [Salesforce DX Project Configuration](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_ws_config.htm) in the _Salesforce DX Developer Guide_ for details about this file.

## Read All About It

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)
