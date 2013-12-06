===============================================
===============================================
JA2 + 1.13 + SDO + AR + AR_SDO + AR_SDO_TBS
===============================================
===============================================
http://tbsgame.net/bbs/index.php?showtopic=67481

1.13: Mod for JA2
http://www.bears-pit.com

SDO: 1.13 Stock Data Overhaul (by Strohmann)
http://www.bears-pit.com/board/ubbthreads.php/topics/328806/1.html

AR: Arulco Revisited (by JAsmine & Bek)
http://www.bears-pit.com/board/ubbthreads.php/topics/298276/1.html

===============================================
起作用的配置文件
===============================================
Profiles\UserProfile_JA2AR（Ja2_sp.ini等）
Data-AR_SDO（CTHConstants.ini、Ja2_Options.INI、Skills_Settings.INI等）

===============================================
存盘文件位置
===============================================
Profiles\UserProfile_JA2AR\SavedGames

===============================================
下面的设置不要去更改
===============================================

【Ja2_sp.ini】

USE_NCTH = 1

【APBPConstants.ini】

AP_CAMOFLAGE = 10

【CTHConstants.ini】

MAX_EFFECTIVE_USE_GRADIENT = TRUE

Ja2_Options.INI

MAX_ITEM_SIZE = 75
MAX_WEAPON_SIZE = 29
USE_NEW_CTH_CALCULATION = TRUE
USE_XML_TILESETS = TRUE
NUM_P_ITEMS = 7
BASE_SIGHT_RANGE = 20
USE_SCOPE_MODES = TRUE
COVER_SYSTEM_CAMOUFLAGE_EFFECTIVENESS = 100
COVER_SYSTEM_TREE_EFFECTIVENESS = 35

===============================================
推荐的设置（默认的配置已经是这些了）
===============================================

【CTHConstants.ini】

IRON_SIGHT_PERFORMANCE_BONUS = 35.0
LASER_PERFORMANCE_BONUS_HIP = 30.0
LASER_PERFORMANCE_BONUS_IRON = 15.0
LASER_PERFORMANCE_BONUS_SCOPE = 5.0
AIM_TOO_CLOSE_SCOPE = -5.0
AIM_STANDING_STANCE = 1.5
AIM_CROUCHING_STANCE = 1.0
AIM_PRONE_STANCE = 0.5
AIM_TOO_CLOSE_SCOPE = -5.0 to compensate for silversurfer's new NCTH code
RANGE_COEFFICIENT = 0.6
GRAVITY_COEFFICIENT = 6.0
AIM_TARGET_INVISIBLE = -200.0 or higher

If you want to nerf auto fire globally, decrease NORMAL_RECOIL_DISTANCE or increase RECOIL_COUNTER_ACCURACY_MIN_ERROR

MAX_EFFECTIVE_RANGE_MULTIPLIER = 1.5 - 2.0
MAX_EFFECTIVE_RANGE_REDUCTION = 0.75 - 0.90

【Ja2_sp.ini】

BOBBY_RAY_QUALITY = 1

【Ja2_Options.INI】

RAISE_TO_ALTWEAPHOLD_READY_APS_PERC = 35
RAISE_FROM_ALTWEAPHOLD_READY_APS_PERCENTAGE = 65
FASTER_SHOT_FROM_ALTWEAPHOLD_PERC = 0
AIMING_PENALY_FROM_ALTWEAPHOLD = 50
AIMING_LEVELS_REDUCTION_ON_ALTWEAPHOLD = 15
SUPPRESSION_EFFECTIVENESS = 120, your preference may vary.
MAX_CTH_PENALTY_FOR_TARGET_SHOCK = 0
MAX_CTH_PENALTY_FROM_SHOCK = 0
EXPLOSIVE_SUPPRESSION_EFFECTIVENESS = 150
STRENGTH_TO_LIFT_HALF_KILO = 1.5 - 1.35
ATTACHMENT_DROP_RATE = 35+
ADMIN_EQUIPMENT_QUALITY_MODIFIER = 1
REGULAR_EQUIPMENT_QUALITY_MODIFIER = 0
ELITE_EQUIPMENT_QUALITY_MODIFIER = -1
GREEN_MILITIA_EQUIPMENT_QUALITY_MODIFIER = 0
REGULAR_MILITIA_EQUIPMENT_QUALITY_MODIFIER = -1
VETERAN_MILITIA_EQUIPMENT_QUALITY_MODIFIER = -2

【Skills_Settings.INI】

DUAL_SHOT_CTH_PENALTY = 50
BONUS_CTH_RIFLES = 3
BONUS_CTH_SNIPER_RIFLES = 5
GUN_DAMAGE_BONUS_FROM_NUM_CLICKS = 5
FIRING_SPEED_BONUS_SHOTGUNS = 5
POSSIBLE_AIM_CLICK_ADDED_SHOTGUNS = 0
FIRING_SPEED_BONUS_PISTOLS = 10
POSSIBLE_AIM_CLICK_ADDED_HANDGUNS = 0
SIGHT_RANGE_BONUS_IN_DARK = 3
BASIC_HEARING_RANGE_BONUS = 2
ONTOP_HEARING_RANGE_BONUS_IN_DARK = 4
SIGHT_RANGE_INCREASED_WITH_SCOPES = 0