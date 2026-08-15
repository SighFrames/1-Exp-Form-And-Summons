This mod sets required EXP for all Drive Form and Summon levels to 1. The goal of this mod is to remove the repetitive form and summon grinding if you've played the game before.

This mod is NOT intended to be used with GOA Randomizer, as that mod already has an option to modify form EXP values.

Once this mod has been downloaded, you can alter the EXP values by editing the FmlvList.yml An example of the FmlvList.yml can be seen below:

```
Valor: #This is the current form you are editing.
- FormId: 1 #This is the ID # for the form. Don't change this.
  FormLevel: 1 #This indicated the form level. Don't change this.
  Experience: 1 #This line determined the amount of experience needed per level
  Ability: 0 #This line indicated the bonus ability/item that is given at this level. You can modify this with the values here: (https://openkh.dev/kh2/dictionary/inventory.html)
  GrowthAbilityLevel: 1 #This indicates the current growth ability level. It should start at 1.
