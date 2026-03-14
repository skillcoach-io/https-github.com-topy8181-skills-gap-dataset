Skill Gap = Skills Required for Role − Skills Present in Profile
Gap Score = Missing Skills / Total Required Skills
function calculateSkillGap(userSkills, roleSkills):

    missingSkills = roleSkills - userSkills

    gapScore = len(missingSkills) / len(roleSkills)

    return gapScore, missingSkills
