set(SOURCES GUIAnalogStickButton.cpp
            GUIControllerButton.cpp
            GUIFeatureButton.cpp
            GUIFeatureControls.cpp
            GUIFeatureFactory.cpp
            GUIFeatureTranslator.cpp
            GUIGameController.cpp
            GUIScalarFeatureButton.cpp
            GUISelectKeyButton.cpp
            GUIThrottleButton.cpp
            GUIWheelButton.cpp
)

set(HEADERS GUIAnalogStickButton.h
            GUIControllerButton.h
            GUIControlTypes.h
            GUIFeatureButton.h
            GUIFeatureControls.h
            GUIFeatureFactory.h
            GUIFeatureTranslator.h
            GUIGameController.h
            GUIScalarFeatureButton.h
            GUISelectKeyButton.h
            GUIThrottleButton.h
            GUIWheelButton.h
)

core_add_library(games_controller_guicontrols)
