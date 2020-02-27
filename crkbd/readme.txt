0 - Colemak
1 - Qwerty
2 - Symbol Nav
3 - Regex
4 - Number Layer
5 - Arrange
6 - Thumb
7 - Function
8 - Mouse

ESC_NUM = LT4(ESC)
BSP_REG =  LT3(BSP)
DEL_REG = LT3(DEL)
MIN_ARR = LT5(-)
TAB_SFT = LSFT(TAB)
SPC_SYM = LT2(SPC)
ENT_THU = LT6(ENT)
FUN_L MO  = LT7

// I need to implement a tristate layer to make the keymap work at all:

uint32_t layer_state_set_user(uint32_t state) {
  state = update_tri_layer_state(state, _SYMBOL, _THUMB, _FUNCTION);
  state = update_tri_layer_state(state, _SYMBOL, _REGEX, _MOUSE);
  return state;
}