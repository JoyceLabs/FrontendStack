function calcBudget() {

    var RequirementTeamTotal = frmBudget.RequirementTeamDays.value * 150;
    var DesignTeamTotal = frmBudget.DesignTeamDays.value * 160;
    var DBATeamTotal = frmBudget.DBATeamDays.value * 200;
    var DevTeamTotal = frmBudget.DevTeamDays.value * 750;
    var TestingTeamTotal = frmBudget.TestingTeamDays.value * 260;

    frmBudget.Total.value = RequirementTeamTotal + DesignTeamTotal + DBATeamTotal + DevTeamTotal + TestingTeamTotal
}