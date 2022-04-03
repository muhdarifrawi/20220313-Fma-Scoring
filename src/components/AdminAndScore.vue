<template>
  <div id="part-1" class="container-fluid custom-top-buffer" v-if="part==1">
    <h1>Administration and Scoring</h1>
    
      <table class="table table-striped">
      <tr class="table-dark">
        <th>#</th>
        <th>Test Item</th>
        <th colspan="3">Score</th>
      </tr>
      <tr class="table-info">
        <th></th>
        <th>Motor</th>
        <th>0</th>
        <th>1</th>
        <th>2</th>
      </tr>
      <tr>
        <td></td>
        <td>Biceps Reflex</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="biceps-reflex-mtr"
            value="0"
            v-model="bicepsReflexMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="biceps-reflex-mtr"
            value="1"
            v-model="bicepsReflexMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="biceps-reflex-mtr"
            value="2"
            v-model="bicepsReflexMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Triceps Reflex</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="triceps-reflex-mtr"
            value="0"
            v-model="tricepsReflexMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="triceps-reflex-mtr"
            value="1"
            v-model="tricepsReflexMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="triceps-reflex-mtr"
            value="2"
            v-model="tricepsReflexMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Shoulder Retraction</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-retraction-mtr"
            value="0"
            v-model="shoulderRetractionMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-retraction-mtr"
            value="1"
            v-model="shoulderRetractionMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-retraction-mtr"
            value="2"
            v-model="shoulderRetractionMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Shoulder Elevation</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-elevation-mtr"
            value="0"
            v-model="shoulderElevationMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-elevation-mtr"
            value="1"
            v-model="shoulderElevationMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-elevation-mtr"
            value="2"
            v-model="shoulderElevationMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Shoulder Abduction</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-abduction-mtr"
            value="0"
            v-model="shoulderAbductionMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-abduction-mtr"
            value="1"
            v-model="shoulderAbductionMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-abduction-mtr"
            value="2"
            v-model="shoulderAbductionMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Shoulder External Rotation</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-external-rotation-mtr"
            value="0"
            v-model="shoulderExternalRotationMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-external-rotation-mtr"
            value="1"
            v-model="shoulderExternalRotationMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-external-rotation-mtr"
            value="2"
            v-model="shoulderExternalRotationMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Elbow Flexion</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="elbow-flexion-mtr"
            value="0"
            v-model="elbowFlexionMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="elbow-flexion-mtr"
            value="1"
            v-model="elbowFlexionMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="elbow-flexion-mtr"
            value="2"
            v-model="elbowFlexionMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Forearm Supination</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-supination-mtr"
            value="0"
            v-model="forearmSupinationMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-supination-mtr"
            value="1"
            v-model="forearmSupinationMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-supination-mtr"
            value="2"
            v-model="forearmSupinationMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Shoulder Adduction/Internal Rotation</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-adduction-internal-rotation-mtr"
            value="0"
            v-model="shoulderAdductionInternalRotationMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-adduction-internal-rotation-mtr"
            value="1"
            v-model="shoulderAdductionInternalRotationMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-adduction-internal-rotation-mtr"
            value="2"
            v-model="shoulderAdductionInternalRotationMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Elbow Extension</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="elbow-extension-mtr"
            value="0"
            v-model="elbowExtensionMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="elbow-extension-mtr"
            value="1"
            v-model="elbowExtensionMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="elbow-extension-mtr"
            value="2"
            v-model="elbowExtensionMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Forearm Pronation</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-pronation-mtr"
            value="0"
            v-model="forearmPronationMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-pronation-mtr"
            value="1"
            v-model="forearmPronationMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-pronation-mtr"
            value="2"
            v-model="forearmPronationMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Hand to Lumbar Spine</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="hand-to-lumbar-spine-mtr"
            value="0"
            v-model="handToLumbarSpineMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="hand-to-lumbar-spine-mtr"
            value="1"
            v-model="handToLumbarSpineMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="hand-to-lumbar-spine-mtr"
            value="2"
            v-model="handToLumbarSpineMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Shoulder Flexion 0&deg; - 90&deg;, Elbow Extended</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-flexion-0-90-elbow-extended-mtr"
            value="0"
            v-model="shoulderFlexion090ElbowExtendedMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-flexion-0-90-elbow-extended-mtr"
            value="1"
            v-model="shoulderFlexion090ElbowExtendedMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-flexion-0-90-elbow-extended-mtr"
            value="2"
            v-model="shoulderFlexion090ElbowExtendedMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Forearm Pronation-Supination, Elbow at 90&deg;</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-pronation-supination-elbow-at-90-mtr"
            value="0"
            v-model="forearmPronationSupinationElbowAt90Mtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-pronation-supination-elbow-at-90-mtr"
            value="1"
            v-model="forearmPronationSupinationElbowAt90Mtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-pronation-supination-elbow-at-90-mtr"
            value="2"
            v-model="forearmPronationSupinationElbowAt90Mtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Shoulder Abduction 0&deg; - 90&deg;, Elbow Extended</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-abduction-0-90-elbow-extended-mtr"
            value="0"
            v-model="shoulderAbduction090ElbowExtendedMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-abduction-0-90-elbow-extended-mtr"
            value="1"
            v-model="shoulderAbduction090ElbowExtendedMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-abduction-0-90-elbow-extended-mtr"
            value="2"
            v-model="shoulderAbduction090ElbowExtendedMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Shoulder Flexion 90&deg; - 180&deg;, Elbow Extended</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-flexion-90-180-elbow-extended-mtr"
            value="0"
            v-model="shoulderFlexion90180ElbowExtendedMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-flexion-90-180-elbow-extended-mtr"
            value="1"
            v-model="shoulderFlexion90180ElbowExtendedMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-flexion-90-180-elbow-extended-mtr"
            value="2"
            v-model="shoulderFlexion90180ElbowExtendedMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Forearm Pronation-Supination, Elbow Extended</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-pronation-supination-elbow-extended-mtr"
            value="0"
            v-model="forearmPronationSupinationElbowExtendedMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-pronation-supination-elbow-extended-mtr"
            value="1"
            v-model="forearmPronationSupinationElbowExtendedMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-pronation-supination-elbow-extended-mtr"
            value="2"
            v-model="forearmPronationSupinationElbowExtendedMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Normal Reflex Activity</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="normal-reflex-activity-mtr"
            value="0"
            v-model="normalReflexActivityMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="normal-reflex-activity-mtr"
            value="1"
            v-model="normalReflexActivityMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="normal-reflex-activity-mtr"
            value="2"
            v-model="normalReflexActivityMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Wrist Stability, Elbow at 90&deg;</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-stability-elbow-at-90-mtr"
            value="0"
            v-model="wristStabilityElbowAt90Mtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-stability-elbow-at-90-mtr"
            value="1"
            v-model="wristStabilityElbowAt90Mtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-stability-elbow-at-90-mtr"
            value="2"
            v-model="wristStabilityElbowAt90Mtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Wrist Flexion/Extension, Elbow at 90&deg;</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-flexion-extension-elbow-at-90-mtr"
            value="0"
            v-model="wristFlexionExtensionElbowAt90Mtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-flexion-extension-elbow-at-90-mtr"
            value="1"
            v-model="wristFlexionExtensionElbowAt90Mtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-flexion-extension-elbow-at-90-mtr"
            value="2"
            v-model="wristFlexionExtensionElbowAt90Mtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Wrist Stability, Elbow Extended</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-stability-elbow-extended-mtr"
            value="0"
            v-model="wristStabilityElbowExtendedMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-stability-elbow-extended-mtr"
            value="1"
            v-model="wristStabilityElbowExtendedMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-stability-elbow-extended-mtr"
            value="2"
            v-model="wristStabilityElbowExtendedMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Wrist Flexion/Extension, Elbow Extended</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-flexion-extension-elbow-extended-mtr"
            value="0"
            v-model="wristFlexionExtensionElbowExtendedMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-flexion-extension-elbow-extended-mtr"
            value="1"
            v-model="wristFlexionExtensionElbowExtendedMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-flexion-extension-elbow-extended-mtr"
            value="2"
            v-model="wristFlexionExtensionElbowExtendedMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Wrist Circumduction</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-circumduction-mtr"
            value="0"
            v-model="wristCircumductionMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-circumduction-mtr"
            value="1"
            v-model="wristCircumductionMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-circumduction-mtr"
            value="2"
            v-model="wristCircumductionMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Fingers Mass Flexion</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="fingers-mass-flexion-mtr"
            value="0"
            v-model="fingersMassFlexionMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="fingers-mass-flexion-mtr"
            value="1"
            v-model="fingersMassFlexionMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="fingers-mass-flexion-mtr"
            value="2"
            v-model="fingersMassFlexionMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Fingers Mass Extension</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="fingers-mass-extension-mtr"
            value="0"
            v-model="fingersMassExtensionMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="fingers-mass-extension-mtr"
            value="1"
            v-model="fingersMassExtensionMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="fingers-mass-extension-mtr"
            value="2"
            v-model="fingersMassExtensionMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Distal Finger Grasp (Hook Grasp)</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="distal-finger-grasp-hook-grasp-mtr"
            value="0"
            v-model="distalFingerGraspHookGraspMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="distal-finger-grasp-hook-grasp-mtr"
            value="1"
            v-model="distalFingerGraspHookGraspMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="distal-finger-grasp-hook-grasp-mtr"
            value="2"
            v-model="distalFingerGraspHookGraspMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Thumb Adduction Grasp</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="thumb-adduction-grasp-mtr"
            value="0"
            v-model="thumbAdductionGraspMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="thumb-adduction-grasp-mtr"
            value="1"
            v-model="thumbAdductionGraspMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="thumb-adduction-grasp-mtr"
            value="2"
            v-model="thumbAdductionGraspMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Thumb to Index Finger Grasp</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="thumb-to-index-finger-grasp-mtr"
            value="0"
            v-model="thumbToIndexFingerGraspMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="thumb-to-index-finger-grasp-mtr"
            value="1"
            v-model="thumbToIndexFingerGraspMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="thumb-to-index-finger-grasp-mtr"
            value="2"
            v-model="thumbToIndexFingerGraspMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Cylindrical Grasp</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="cylindrical-grasp-mtr"
            value="0"
            v-model="cylindricalGraspMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="cylindrical-grasp-mtr"
            value="1"
            v-model="cylindricalGraspMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="cylindrical-grasp-mtr"
            value="2"
            v-model="cylindricalGraspMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Spherical Grasp</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="spherical-grasp-mtr"
            value="0"
            v-model="sphericalGraspMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="spherical-grasp-mtr"
            value="1"
            v-model="sphericalGraspMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="spherical-grasp-mtr"
            value="2"
            v-model="sphericalGraspMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Tremor</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="tremor-mtr"
            value="0"
            v-model="tremorMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="tremor-mtr"
            value="1"
            v-model="tremorMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="tremor-mtr"
            value="2"
            v-model="tremorMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Dysmetria</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="dysmetria-mtr"
            value="0"
            v-model="dysmetriaMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="dysmetria-mtr"
            value="1"
            v-model="dysmetriaMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="dysmetria-mtr"
            value="2"
            v-model="dysmetriaMtr"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Speed</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="speed-mtr"
            value="0"
            v-model="speedMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="speed-mtr"
            value="1"
            v-model="speedMtr"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="speed-mtr"
            value="2"
            v-model="speedMtr"
          />
        </td>
      </tr>
      <tr class="table-info">
        <th></th>
        <th>Sensation</th>
        <th>0</th>
        <th>1</th>
        <th>2</th>
      </tr>
      <tr>
        <td></td>
        <td>Light Touch - Upper Arm, Forearm</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="light-touch-upper-arm-forearm-snt"
            value="0"
            v-model="lightTouchUpperArmForearmSnt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="light-touch-upper-arm-forearm-snt"
            value="1"
            v-model="lightTouchUpperArmForearmSnt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="light-touch-upper-arm-forearm-snt"
            value="2"
            v-model="lightTouchUpperArmForearmSnt"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Light Touch - Palmar Surface of Hand</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="light-touch-palmar-surface-of-hand-snt"
            value="0"
            v-model="lightTouchPalmarSurfaceOfHandSnt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="light-touch-palmar-surface-of-hand-snt"
            value="1"
            v-model="lightTouchPalmarSurfaceOfHandSnt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="light-touch-palmar-surface-of-hand-snt"
            value="2"
            v-model="lightTouchPalmarSurfaceOfHandSnt"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Position - Shoulder</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="position-shoulder-snt"
            value="0"
            v-model="positionShoulderSnt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="position-shoulder-snt"
            value="1"
            v-model="positionShoulderSnt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="position-shoulder-snt"
            value="2"
            v-model="positionShoulderSnt"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Position - Elbow</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="position-elbow-snt"
            value="0"
            v-model="positionElbowSnt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="position-elbow-snt"
            value="1"
            v-model="positionElbowSnt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="position-elbow-snt"
            value="2"
            v-model="positionElbowSnt"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Position - Wrist</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="position-wrist-snt"
            value="0"
            v-model="positionWristSnt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="position-wrist-snt"
            value="1"
            v-model="positionWristSnt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="position-wrist-snt"
            value="2"
            v-model="positionWristSnt"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Position - Thumb</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="position-thumb-snt"
            value="0"
            v-model="positionThumbSnt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="position-thumb-snt"
            value="1"
            v-model="positionThumbSnt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="position-thumb-snt"
            value="2"
            v-model="positionThumbSnt"
          />
        </td>
      </tr>
      <tr class="table-info">
        <th></th>
        <th>Passive Joint Motion</th>
        <th>0</th>
        <th>1</th>
        <th>2</th>
      </tr>
      <tr>
        <td></td>
        <td>Shoulder Flexion (0&deg; - 180 &deg;)</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-flexion-0-180-pjt"
            value="0"
            v-model="shoulderFlexion0180Pjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-flexion-0-180-pjt"
            value="1"
            v-model="shoulderFlexion0180Pjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-flexion-0-180-pjt"
            value="2"
            v-model="shoulderFlexion0180Pjt"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Shoulder Abduction (0&deg; - 90 &deg;)</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-abduction-0-90-pjt"
            value="0"
            v-model="shoulderAbduction090Pjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-abduction-0-90-pjt"
            value="1"
            v-model="shoulderAbduction090Pjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-abduction-0-90-pjt"
            value="2"
            v-model="shoulderAbduction090Pjt"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>External Rotation</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="external-rotation-pjt"
            value="0"
            v-model="externalRotationPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="external-rotation-pjt"
            value="1"
            v-model="externalRotationPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="external-rotation-pjt"
            value="2"
            v-model="externalRotationPjt"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Internal Rotation</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="internal-rotation-pjt"
            value="0"
            v-model="internalRotationPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="internal-rotation-pjt"
            value="1"
            v-model="internalRotationPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="internal-rotation-pjt"
            value="2"
            v-model="internalRotationPjt"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Elbow Flexion</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="elbow-flexion-pjt"
            value="0"
            v-model="elbowFlexionPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="elbow-flexion-pjt"
            value="1"
            v-model="elbowFlexionPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="elbow-flexion-pjt"
            value="2"
            v-model="elbowFlexionPjt"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Elbow Extension</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="elbow-extension-pjt"
            value="0"
            v-model="elbowExtensionPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="elbow-extension-pjt"
            value="1"
            v-model="elbowExtensionPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="elbow-extension-pjt"
            value="2"
            v-model="elbowExtensionPjt"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Forearm Pronation</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-pronation-pjt"
            value="0"
            v-model="forearmPronationPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-pronation-pjt"
            value="1"
            v-model="forearmPronationPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-pronation-pjt"
            value="2"
            v-model="forearmPronationPjt"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Forearm Supination</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-supination-pjt"
            value="0"
            v-model="forearmSupinationPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-supination-pjt"
            value="1"
            v-model="forearmSupinationPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-supination-pjt"
            value="2"
            v-model="forearmSupinationPjt"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Wrist Flexion</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-flexion-pjt"
            value="0"
            v-model="wristFlexionPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-flexion-pjt"
            value="1"
            v-model="wristFlexionPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-flexion-pjt"
            value="2"
            v-model="wristFlexionPjt"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Wrist Extension</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-extension-pjt"
            value="0"
            v-model="wristExtensionPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-extension-pjt"
            value="1"
            v-model="wristExtensionPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-extension-pjt"
            value="2"
            v-model="wristExtensionPjt"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Fingers Flexion</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="fingers-flexion-pjt"
            value="0"
            v-model="fingersFlexionPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="fingers-flexion-pjt"
            value="1"
            v-model="fingersFlexionPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="fingers-flexion-pjt"
            value="2"
            v-model="fingersFlexionPjt"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Fingers Extension</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="fingers-extension-pjt"
            value="0"
            v-model="fingersExtensionPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="fingers-extension-pjt"
            value="1"
            v-model="fingersExtensionPjt"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="fingers-extension-pjt"
            value="2"
            v-model="fingersExtensionPjt"
          />
        </td>
      </tr>
      <tr class="table-info">
        <th></th>
        <th>Joint Pain</th>
        <th>0</th>
        <th>1</th>
        <th>2</th>
      </tr>
      <tr>
        <td></td>
        <td>Shoulder Flexion (0&deg; - 180 &deg;)</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-flexion-0-180-jp"
            value="0"
            v-model="shoulderFlexion0180Jp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-flexion-0-180-jp"
            value="1"
            v-model="shoulderFlexion0180Jp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-flexion-0-180-jp"
            value="2"
            v-model="shoulderFlexion0180Jp"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Shoulder Abduction (0&deg; - 90 &deg;)</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-abduction-0-90-jp"
            value="0"
            v-model="shoulderAbduction090Jp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-abduction-0-90-jp"
            value="1"
            v-model="shoulderAbduction090Jp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="shoulder-abduction-0-90-jp"
            value="2"
            v-model="shoulderAbduction090Jp"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>External Rotation</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="external-rotation-jp"
            value="0"
            v-model="externalRotationJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="external-rotation-jp"
            value="1"
            v-model="externalRotationJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="external-rotation-jp"
            value="2"
            v-model="externalRotationJp"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Internal Rotation</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="internal-rotation-jp"
            value="0"
            v-model="internalRotationJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="internal-rotation-jp"
            value="1"
            v-model="internalRotationJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="internal-rotation-jp"
            value="2"
            v-model="internalRotationJp"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Elbow Flexion</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="elbow-flexion-jp"
            value="0"
            v-model="elbowFlexionJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="elbow-flexion-jp"
            value="1"
            v-model="elbowFlexionJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="elbow-flexion-jp"
            value="2"
            v-model="elbowFlexionJp"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Elbow Extension</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="elbow-extension-jp"
            value="0"
            v-model="elbowExtensionJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="elbow-extension-jp"
            value="1"
            v-model="elbowExtensionJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="elbow-extension-jp"
            value="2"
            v-model="elbowExtensionJp"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Forearm Pronation</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-pronation-jp"
            value="0"
            v-model="forearmPronationJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-pronation-jp"
            value="1"
            v-model="forearmPronationJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-pronation-jp"
            value="2"
            v-model="forearmPronationJp"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Forearm Supination</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-supination-jp"
            value="0"
            v-model="forearmSupinationJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-supination-jp"
            value="1"
            v-model="forearmSupinationJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="forearm-supination-jp"
            value="2"
            v-model="forearmSupinationJp"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Wrist Flexion</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-flexion-jp"
            value="0"
            v-model="wristFlexionJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-flexion-jp"
            value="1"
            v-model="wristFlexionJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-flexion-jp"
            value="2"
            v-model="wristFlexionJp"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Wrist Extension</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-extension-jp"
            value="0"
            v-model="wristExtensionJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-extension-jp"
            value="1"
            v-model="wristExtensionJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="wrist-extension-jp"
            value="2"
            v-model="wristExtensionJp"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Fingers Flexion</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="fingers-flexion-jp"
            value="0"
            v-model="fingersFlexionJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="fingers-flexion-jp"
            value="1"
            v-model="fingersFlexionJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="fingers-flexion-jp"
            value="2"
            v-model="fingersFlexionJp"
          />
        </td>
      </tr>
      <tr>
        <td></td>
        <td>Fingers Extension</td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="fingers-extension-jp"
            value="0"
            v-model="fingersExtensionJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="fingers-extension-jp"
            value="1"
            v-model="fingersExtensionJp"
          />
        </td>
        <td>
          <input
            class="form-check-input"
            type="radio"
            name="fingers-extension-jp"
            value="2"
            v-model="fingersExtensionJp"
          />
        </td>
      </tr>
    </table>
    <table class="table table-striped">
      <tr>
        <th>Total Score</th>
        <th>{{totalScore}}/126</th>
      </tr>
      <tr>
        <th>A - Motor</th>
        <th>{{motorA}}/66</th>
      </tr>
      <tr>
        <td>shoulder/Elbow/Forearm</td>
        <td>{{sef}}/36</td>
      </tr>
      <tr>
        <td>Wrist</td>
        <td>{{wrist}}/10</td>
      </tr>
      <tr>
        <td>Hand</td>
        <td>{{hand}}/14</td>
      </tr>
      <tr>
        <td>Coordination/Speed</td>
        <td>{{cs}}/6</td>
      </tr>
      <tr>
        <th>B - Sensation</th>
        <th>{{sensationB}}/12</th>
      </tr>
      <tr>
        <th>C - Passive Joint Motion</th>
        <th>{{pjtC}}/24</th>
      </tr>
      <tr>
        <th>D - Joint Pain</th>
        <th>{{jpD}}/24</th>
      </tr>
    </table>
    </div>
  <div id="part-2" class="container-fluid custom-top-buffer" v-if="part==2">
    <h1>Administration and Scoring</h1>
    <table class="table table-striped">
      <tr>
        <th>Score</th>
        <th>Test Item</th>
      </tr>
      <tr>
        <td>{{wristCircumductionMtr}}</td>
        <td>Wrist Circumduction</td>
      </tr>
      <tr>
        <td>{{distalFingerGraspHookGraspMtr}}</td>
        <td>Distal Finger Grasp (Hook Grasp)</td>
      </tr>
      <tr>
        <td>{{shoulderFlexion90180ElbowExtendedMtr}}</td>
        <td>Shoulder Flexion 90&deg; - 180&deg;, elbow extended</td>
      </tr>
      <tr>
        <td>{{sphericalGraspMtr}}</td>
        <td>Spherical Grasp</td>
      </tr>
      <tr>
        <td>{{thumbAdductionGraspMtr}}</td>
        <td>Thumb Adduction Grasp</td>
      </tr>
      <tr>
        <td>{{wristFlexionExtensionElbowExtendedMtr}}</td>
        <td>Wrist Flexion/Extension, Elbow Extended</td>
      </tr>
      <tr>
        <td>{{forearmPronationSupinationElbowExtendedMtr}}</td>
        <td>Forearm Pronation-Supination, Elow Extended</td>
      </tr>
      <tr>
        <td>{{wristStabilityElbowExtendedMtr}}</td>
        <td>Wrist Stability, Elbow Extended</td>
      </tr>
      <tr>
        <td>{{speedMtr}}</td>
        <td>Speed</td>
      </tr>
      <tr>
        <td>{{forearmSupinationMtr}}</td>
        <td>Forearm Supination</td>
      </tr>
      <tr>
        <td>{{shoulderAbduction090ElbowExtendedMtr}}</td>
        <td>Shoulder Abduction 0&deg; - 90&deg;, Elbow Extended</td>
      </tr>
      <tr>
        <td>{{dysmetriaMtr}}</td>
        <td>Dysmetria</td>
      </tr>
      <tr>
        <td>{{shoulderExternalRotationMtr}}</td>
        <td>Shoulder External Rotation</td>
      </tr>
      <tr>
        <td>{{wristStabilityElbowAt90Mtr}}</td>
        <td>Wrist Stability, Elbow at 90&deg;</td>
      </tr>
      <tr>
        <td>{{wristFlexionExtensionElbowAt90Mtr}}</td>
        <td>Wrist Flexion/Extension, Elbow at 90&deg;</td>
      </tr>
      <tr>
        <td>{{thumbToIndexFingerGraspMtr}}</td>
        <td>Thumb to Index Finger Grasp</td>
      </tr>
      <tr>
        <td>{{shoulderRetractionMtr}}</td>
        <td>Shoulder Retraction</td>
      </tr>
      <tr>
        <td>{{forearmPronationSupinationElbowAt90Mtr}}</td>
        <td>Forearm Pronation-Supination, Elbow at 90&deg;</td>
      </tr>
      <tr>
        <td>{{shoulderFlexion090ElbowExtendedMtr}}</td>
        <td>Shoulder Flexion 0&deg;-90&deg;, Elbow Extended</td>
      </tr>
      <tr>
        <td>{{handToLumbarSpineMtr}}</td>
        <td>Hand to Lumbar Spine</td>
      </tr>
      <tr>
        <td>{{shoulderAbductionMtr}}</td>
        <td>Shoulder Abduction</td>
      </tr>
      <tr>
        <td>{{elbowExtensionMtr}}</td>
        <td>Elbow Extension</td>
      </tr>
      <tr>
        <td>{{forearmPronationMtr}}</td>
        <td>Forearm Pronation</td>
      </tr>
      <tr>
        <td>{{tremorMtr}}</td>
        <td>Tremor</td>
      </tr>
      <tr>
        <td>{{cylindricalGraspMtr}}</td>
        <td>Cylindrical Grasp</td>
      </tr>
      <tr>
        <td>{{fingersMassExtensionMtr}}</td>
        <td>Finger Mass Extension</td>
      </tr>
      <tr>
        <td>{{shoulderElevationMtr}}</td>
        <td>Shoulder Elevation</td>
      </tr>
      <tr>
        <td>{{fingersMassFlexionMtr}}</td>
        <td>Finger Mass Flexion</td>
      </tr>
      <tr>
        <td>{{shoulderAdductionInternalRotationMtr}}</td>
        <td>Shoulder Adduction/Internal Rotation</td>
      </tr>
      <tr>
        <td>{{elbowFlexionMtr}}</td>
        <td>Elbow Flexion</td>
      </tr>
    </table>
  </div>
  <div id="part-3" class="container-fluid custom-top-buffer" v-if="part==3">
    <h1>Administration and Scoring</h1>
    <div id="alert-banner">
    </div>
    <div id="activity-bank" class="container">
      <div id="item-1" class="row">
        <div class="item col border border-dark p-3">
          <p>Wrist Circumduction</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[1]}" @click="isMuted[1] = !isMuted[1]">Stirring your drink with a spoon</p>
          <p :class="{'text-muted':isMuted[2]}" @click="isMuted[2] = !isMuted[2]">Drawing circles, spirals, figure-of-8 or the infinity sign</p>
        </div>
      </div>
      <div id="item-2" class="row">
        <div class="item col border border-dark p-3">
          <p>Distal finger grasp (Hook Grasp)</p>
          </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[3]}" @click="isMuted[3] = !isMuted[3]">Carrying a container or holding a plastic bag by its handles</p>
          <p :class="{'text-muted':isMuted[4]}" @click="isMuted[4] = !isMuted[4]">Opening a tupperware</p>
          <p :class="{'text-muted':isMuted[5]}" @click="isMuted[5] = !isMuted[5]">Scratching your back</p>
        </div>
      </div>
      <div id="item-3" class="row">
        <div class="item col border border-dark p-3">
          <p>Shoulder Flexion 90&deg; - 180&deg;, Elbow Extended</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[6]}" @click="isMuted[6] = !isMuted[6]">Taking an item from a high shelf/cupboard</p>
          <p :class="{'text-muted':isMuted[7]}" @click="isMuted[7] = !isMuted[7]">Wiping a tall mirror or window</p>
        </div>
      </div>
      <div id="item-4" class="row">
        <div class="item col border border-dark p-3">
          <p>Spherical Grasp</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[8]}" @click="isMuted[8] = !isMuted[8]">Holding a ball</p>
          <p :class="{'text-muted':isMuted[9]}" @click="isMuted[9] = !isMuted[9]">Turning a round door knob</p>
        </div>
      </div>
      <div id="item-5" class="row">
        <div class="item col border border-dark p-3">
          <p>Thumb Adduction Grasp</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[10]}" @click="isMuted[10] = !isMuted[10]">Holding a key</p>
          <p :class="{'text-muted':isMuted[11]}" @click="isMuted[11] = !isMuted[11]">Swiping a credit card through a slot</p>
          <p :class="{'text-muted':isMuted[12]}" @click="isMuted[12] = !isMuted[12]">Pressing the buttons on the TV remote control</p>
          <p :class="{'text-muted':isMuted[13]}" @click="isMuted[13] = !isMuted[13]">Pressing or pinching Bluetac/plasticine</p>
        </div>
      </div>
      <div id="item-6" class="row">
        <div class="item col border border-dark p-3">
          <p>Wrist Flexion/Extension, Elbow Extended</p>
        </div>
        <div class="activity col border border-dark p-3" >
          <p :class="{'text-muted':isMuted[14]}" @click="isMuted[14] = !isMuted[14]">Painting up/down strokes on a piece of paper on the wall</p>
          <p :class="{'text-muted':isMuted[15]}" @click="isMuted[15] = !isMuted[15]">Shoo the fly</p>
          <p :class="{'text-muted':isMuted[16]}" @click="isMuted[16] = !isMuted[16]">Placing something into a container</p>
        </div>
      </div>
      <div id="item-7" class="row">
        <div class="item col border border-dark p-3">
          <p>Forearm Pronation-Supination, Elbow Extended</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[17]}" @click="isMuted[17] = !isMuted[17]">Pouring a glass of water (glass placed at a distance)</p>
          <p :class="{'text-muted':isMuted[18]}" @click="isMuted[18] = !isMuted[18]">Turning a door knob (door at arms length)</p>
          <p :class="{'text-muted':isMuted[19]}" @click="isMuted[19] = !isMuted[19]">Wiping or drawing a large semi-circle on a whiteboard/mirror</p>
        </div>
      </div>
      <div id="item-8" class="row">
        <div class="item col border border-dark p-3">
          <p>Wrist Stability, Elbow Extended</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[20]}" @click="isMuted[20] = !isMuted[20]">Wiping a mirror/window</p>
          <p :class="{'text-muted':isMuted[21]}" @click="isMuted[21] = !isMuted[21]">Playing a balloon badminton</p>
        </div>
      </div>
      <div id="item-9" class="row">
        <div class="item col border border-dark p-3">
          <p>Speed</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[22]}" @click="isMuted[22] = !isMuted[22]">Timing yourself to complete a task</p>
          <p :class="{'text-muted':isMuted[23]}" @click="isMuted[23] = !isMuted[23]">Playing a game of Snap</p>
          <p :class="{'text-muted':isMuted[24]}" @click="isMuted[24] = !isMuted[24]">Following a Zumba choreography</p>
        </div>
      </div>
      <div id="item-10" class="row">
        <div class="item col border border-dark p-3">
          <p>Forearm Supination</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[25]}" @click="isMuted[25] = !isMuted[25]">Balancing coins/beads with an open palm</p>
          <p :class="{'text-muted':isMuted[26]}" @click="isMuted[26] = !isMuted[26]">Receiving items with your palms facing upwards</p>
        </div>
      </div>
      <div id="item-11" class="row">
        <div class="item col border border-dark p-3">
          <p>Shoulder Abduction 0&deg; - 90&deg;</p>
        </div>
        <div class="activity  col border border-dark p-3">
          <p :class="{'text-muted':isMuted[27]}" @click="isMuted[27] = !isMuted[27]">Placing your arm around your caregiver's shoulders</p>
          <p :class="{'text-muted':isMuted[28]}" @click="isMuted[28] = !isMuted[28]">Reaching for items with your palms facing upwards</p>
        </div>
      </div>
      <div id="item-12" class="row">
        <div class="item col border border-dark p-3">
          <p>Dysmetria</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[29]}" @click="isMuted[29] = !isMuted[29]">Putting coins into coin box or playing a game of connect-four</p>
          <p :class="{'text-muted':isMuted[30]}" @click="isMuted[30] = !isMuted[30]">Completeing a craft project using Hama beads/water beads</p>
        </div>
      </div>
      <div id="item-13" class="row">
        <div class="item col border border-dark p-3">
          <p>Shoulder External Rotation</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[31]}" @click="isMuted[31] = !isMuted[31]">Opening the curtains</p>
          <p :class="{'text-muted':isMuted[32]}" @click="isMuted[32] = !isMuted[32]">Turning the pages of the newspaper</p>
        </div>
      </div>
      <div id="item-14" class="row">
        <div class="item col border border-dark p-3">
          <p>Wrist Stability, Elbow at 90&deg;</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[33]}" @click="isMuted[33] = !isMuted[33]">Holding a cup of water</p>
          <p :class="{'text-muted':isMuted[34]}" @click="isMuted[34] = !isMuted[34]">Holding a tray</p>
          <p :class="{'text-muted':isMuted[35]}" @click="isMuted[35] = !isMuted[35]">Threading beads</p>
        </div>
      </div>
      <div id="item-15" class="row">
        <div class="item col border border-dark p-3">
          <p>Wrist Flexion/Extesion, Elbow at 90&deg;</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[36]}" @click="isMuted[36] = !isMuted[36]">Catching, throwing and holding a ball</p>
          <p :class="{'text-muted':isMuted[37]}" @click="isMuted[37] = !isMuted[37]">Bouncing a ball</p>
        </div>
      </div>
      <div id="item-16" class="row">
        <div class="item col border border-dark p-3">
          <p>Thumb to Index Finger Grasp</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[38]}" @click="isMuted[38] = !isMuted[38]">Practicing doing up buttons</p>
          <p :class="{'text-muted':isMuted[39]}" @click="isMuted[39] = !isMuted[39]">Putting coins into slots (e.g. coin box)</p>
          <p :class="{'text-muted':isMuted[40]}" @click="isMuted[40] = !isMuted[40]">Zipping up/down a zipper</p>
        </div>
      </div>
      <div id="item-17" class="row">
        <div class="item col border border-dark p-3">
          <p>Shoulder Retraction</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[41]}" @click="isMuted[41] = !isMuted[41]">Imagining you are holding a tennis ball between your shoulder blades</p>
          <p :class="{'text-muted':isMuted[42]}" @click="isMuted[42] = !isMuted[42]">Doing scapular push-ups</p>
          <p :class="{'text-muted':isMuted[43]}" @click="isMuted[43] = !isMuted[43]">Practising the Cat and Cow yoga pose</p>
          <p :class="{'text-muted':isMuted[44]}" @click="isMuted[44] = !isMuted[44]">Mopping the floor (pulling back the mop)</p>
        </div>
      </div>
      <div id="item-18" class="row">
        <div class="item col border border-dark p-3">
          <p>Forearm Pronation-Supination, Elbow at 90&deg;</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[45]}" @click="isMuted[45] = !isMuted[45]">Pouring things out of cups</p>
          <p :class="{'text-muted':isMuted[46]}" @click="isMuted[46] = !isMuted[46]">Turning a door knob</p>
          <p :class="{'text-muted':isMuted[47]}" @click="isMuted[47] = !isMuted[47]">Flipping newspaper/pages/cards</p>
        </div>
      </div>
      <div id="item-19" class="row">
        <div class="item col border border-dark p-3">
          <p>Shoulder Flexion 0&deg; - 90&deg;, Elbow Extended</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[48]}" @click="isMuted[48] = !isMuted[48]">Placing items onto a table at arm's length</p>
          <p :class="{'text-muted':isMuted[49]}" @click="isMuted[49] = !isMuted[49]">Clipping something onto the IV drop stand</p>
        </div>
      </div>
      <div id="item-20" class="row">
        <div class="item col border border-dark p-3">
          <p>Hand to Lumbar Spine</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[50]}" @click="isMuted[50] = !isMuted[50]">Passing items behind your back</p>
          <p :class="{'text-muted':isMuted[51]}" @click="isMuted[51] = !isMuted[51]">Applying cream onto your lower back</p>
        </div>
      </div>
      <div id="item-21" class="row">
        <div class="item col border border-dark p-3">
          <p>Shoulder Abduction</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[52]}" @click="isMuted[52] = !isMuted[52]">Placing arm around caregiver's shoulder</p>
          <p :class="{'text-muted':isMuted[53]}" @click="isMuted[53] = !isMuted[53]">Stretching your arm to unfold a towel or to read the newspaper</p>
          <p :class="{'text-muted':isMuted[54]}" @click="isMuted[54] = !isMuted[54]">Hang items on the drip stand</p>
        </div>
      </div>
      <div id="item-22" class="row">
        <div class="item col border border-dark p-3">
          <p>Elbow Extension</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[55]}" @click="isMuted[55] = !isMuted[55]">Throw a ball</p>
          <p :class="{'text-muted':isMuted[56]}" @click="isMuted[56] = !isMuted[56]">Reaching forward</p>
          <p :class="{'text-muted':isMuted[57]}" @click="isMuted[57] = !isMuted[57]">Playing bowling</p>
        </div>
      </div>
      <div id="item-23" class="row">
        <div class="item col border border-dark p-3">
          <p>Forearm Pronation</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[58]}" @click="isMuted[58] = !isMuted[58]">Turning a door knob</p>
          <p :class="{'text-muted':isMuted[59]}" @click="isMuted[59] = !isMuted[59]">Turning over cups</p>
          <p :class="{'text-muted':isMuted[60]}" @click="isMuted[60] = !isMuted[60]">Folding your clothes</p>
        </div>
      </div>
      <div id="item-24" class="row">
        <div class="item col border border-dark p-3">
          <p>Tremor</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[61]}" @click="isMuted[61] = !isMuted[61]">Rolling and catching marbles</p>
          <p :class="{'text-muted':isMuted[62]}" @click="isMuted[62] = !isMuted[62]">Pinning pegs onto small targets</p>
          <p :class="{'text-muted':isMuted[63]}" @click="isMuted[63] = !isMuted[63]">Playing the xylophone</p>
        </div>
      </div>
      <div id="item-25" class="row">
        <div class="item col border border-dark p-3">
          <p>Cylindrical Grasp</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[64]}" @click="isMuted[64] = !isMuted[64]">Holding onto a bottle of water</p>
          <p :class="{'text-muted':isMuted[65]}" @click="isMuted[65] = !isMuted[65]">Holding onto a cup (while pouring water into it)</p>
        </div>
      </div>
      <div id="item-26" class="row">
        <div class="item col border border-dark p-3">
          <p>Finger Mass Extension</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[66]}" @click="isMuted[66] = !isMuted[66]">Releasing your grasp on medicine bottles</p>
          <p :class="{'text-muted':isMuted[67]}" @click="isMuted[67] = !isMuted[67]">Throwing acn catching squeeze balls</p>
          <p :class="{'text-muted':isMuted[68]}" @click="isMuted[68] = !isMuted[68]">Opening your fingers wide to place on a large bottle</p>
        </div>
      </div>
      <div id="item-27" class="row">
        <div class="item col border border-dark p-3"> 
          <p>Shoulder Elevation</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[69]}" @click="isMuted[69] = !isMuted[69]">Practicing 'I don't know' with shoulder shrugs</p>
          <p :class="{'text-muted':isMuted[70]}" @click="isMuted[70] = !isMuted[70]">Holding the phone between your head and shoulder</p>
        </div>
      </div>
      <div id="item-28" class="row">
        <div class="item col border border-dark p-3">
          <p>Finger Mass Flexion</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[71]}" @click="isMuted[71] = !isMuted[71]">Holding onto a small bottle</p>
          <p :class="{'text-muted':isMuted[72]}" @click="isMuted[72] = !isMuted[72]">Squeezing a sponge/towel</p>
          <p :class="{'text-muted':isMuted[73]}" @click="isMuted[73] = !isMuted[73]">Gathering tissue/paper into a ball</p>
        </div>
      </div>
      <div id="item-29" class="row">
        <div class="item col border border-dark p-3">
          <p>Shoulder Adduction/Internal Rotation</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[74]}" @click="isMuted[74] = !isMuted[74]">Closing curtains</p>
          <p :class="{'text-muted':isMuted[75]}" @click="isMuted[75] = !isMuted[75]">Applying lotion on your less affected arm and leg</p>
          <p :class="{'text-muted':isMuted[76]}" @click="isMuted[76] = !isMuted[76]">Turning the pages of the newspaper</p>
          <p :class="{'text-muted':isMuted[77]}" @click="isMuted[77] = !isMuted[77]">Cleaning the table</p>
        </div>
      </div>
      <div id="item-30" class="row">
        <div class="item col border border-dark p-3">
          <p>Elbow Flexion</p>
        </div>
        <div class="activity col border border-dark p-3">
          <p :class="{'text-muted':isMuted[78]}" @click="isMuted[78] = !isMuted[78]">Bringing a cup to your mouth</p>
          <p :class="{'text-muted':isMuted[79]}" @click="isMuted[79] = !isMuted[79]">Using wet tissue to clean your face</p>
          <p :class="{'text-muted':isMuted[80]}" @click="isMuted[80] = !isMuted[80]">Bringing a comb to your head</p>
        </div>
      </div>
    </div>
  </div>

<nav id="btn-controls" class="container-fluid d-flex justify-content-center" aria-label="part controls">
  <ul class="pagination">
    <li class="page-item"><button class="btn btn-light page-item me-1" @click="decreasePage">Previous</button></li>
    <li class="page-item"><span class="btn btn-light page-item">Page {{part}}</span></li>
    <li class="page-item"><button class="btn btn-light page-item ms-1" @click="increasePage">Next</button></li>
  </ul>
</nav>
<button class="btn btn-light page-item" @click="computeScore">compute</button>
</template>
<script>
export default {
  name: "Main",
  data() {
    return {
      test: "test-score",
      isMuted: {
        1:true,
        2:true,
        3:true,
        4:true,
        5:true,
        6:true,
        7:true,
        8:true,
        9:true,
        10:true,
        11:true,
        12:true,
        13:true,
        14:true,
        15:true,
        16:true,
        18:true,
        19:true,
        20:true,
        21:true,
        22:true,
        23:true,
        24:true,
        25:true,
        26:true,
        27:true,
        28:true,
        29:true,
        30:true,
        31:true,
        32:true,
        33:true,
        34:true,
        35:true,
        36:true,
        37:true,
        38:true,
        39:true,
        40:true,
        41:true,
        42:true,
        43:true,
        44:true,
        45:true,
        46:true,
        47:true,
        48:true,
        49:true,
        50:true,
        51:true,
        52:true,
        53:true,
        54:true,
        55:true,
        56:true,
        57:true,
        58:true,
        59:true,
        60:true,
        61:true,
        62:true,
        63:true,
        64:true,
        65:true,
        66:true,
        67:true,
        68:true,
        69:true,
        70:true,
        71:true,
        72:true,
        73:true,
        74:true,
        75:true,
        76:true,
        77:true,
        78:true,
        79:true,
        80:true,
      },
      part:1,
      bicepsReflexMtr: null,
      tricepsReflexMtr: null,
      shoulderRetractionMtr: null,
      shoulderElevationMtr: null,
      shoulderAbductionMtr: null,
      shoulderExternalRotationMtr: null,
      elbowFlexionMtr: null,
      forearmSupinationMtr: null,
      shoulderAdductionInternalRotationMtr: null,
      elbowExtensionMtr: null,
      forearmPronationMtr: null,
      handToLumbarSpineMtr: null,
      shoulderFlexion090ElbowExtendedMtr: null,
      forearmPronationSupinationElbowAt90Mtr: null,
      shoulderAbduction090ElbowExtendedMtr: null,
      shoulderFlexion90180ElbowExtendedMtr: null,
      forearmPronationSupinationElbowExtendedMtr: null,
      normalReflexActivityMtr: null,
      wristStabilityElbowAt90Mtr: null,
      wristFlexionExtensionElbowAt90Mtr: null,
      wristStabilityElbowExtendedMtr: null,
      wristFlexionExtensionElbowExtendedMtr: null,
      wristCircumductionMtr: null,
      fingersMassFlexionMtr: null,
      fingersMassExtensionMtr: null,
      distalFingerGraspHookGraspMtr: null,
      thumbAdductionGraspMtr: null,
      thumbToIndexFingerGraspMtr: null,
      cylindricalGraspMtr: null,
      sphericalGraspMtr: null,
      tremorMtr: null,
      dysmetriaMtr: null,
      speedMtr: null,
      lightTouchUpperArmForearmSnt: null,
      lightTouchPalmarSurfaceOfHandSnt: null,
      positionShoulderSnt: null,
      positionElbowSnt: null,
      positionWristSnt: null,
      positionThumbSnt: null,
      shoulderFlexion0180Pjt: null,
      shoulderAbduction090Pjt: null,
      externalRotationPjt: null,
      internalRotationPjt: null,
      elbowFlexionPjt: null,
      elbowExtensionPjt: null,
      forearmPronationPjt: null,
      forearmSupinationPjt: null,
      wristFlexionPjt: null,
      wristExtensionPjt: null,
      fingersFlexionPjt: null,
      fingersExtensionPjt: null,
      shoulderFlexion0180Jp: null,
      shoulderAbduction090Jp: null,
      externalRotationJp: null,
      internalRotationJp: null,
      elbowFlexionJp: null,
      elbowExtensionJp: null,
      forearmPronationJp: null,
      forearmSupinationJp: null,
      wristFlexionJp: null,
      wristExtensionJp: null,
      fingersFlexionJp: null,
      fingersExtensionJp: null,
      formData:[],
    };
  },
  computed: {
    totalScore(){
        return this.motorA + this.sensationB + this.pjtC + this.jpD
    },
    motorA() {
        return parseInt(this.sef) + parseInt(this.wrist) + parseInt(this.hand) + parseInt(this.cs)
    },
    sef() {
        return(
            parseInt(this.bicepsReflexMtr) +
            parseInt(this.tricepsReflexMtr) +
            parseInt(this.shoulderRetractionMtr) +
            parseInt(this.shoulderElevationMtr) +
            parseInt(this.shoulderAbductionMtr) +
            parseInt(this.shoulderExternalRotationMtr) +
            parseInt(this.elbowFlexionMtr) +
            parseInt(this.forearmSupinationMtr) +
            parseInt(this.shoulderAdductionInternalRotationMtr) +
            parseInt(this.elbowExtensionMtr) +
            parseInt(this.forearmPronationMtr) +
            parseInt(this.handToLumbarSpineMtr) +
            parseInt(this.shoulderFlexion090ElbowExtendedMtr) +
            parseInt(this.forearmPronationSupinationElbowAt90Mtr) +
            parseInt(this.shoulderAbduction090ElbowExtendedMtr) +
            parseInt(this.shoulderFlexion90180ElbowExtendedMtr) +
            parseInt(this.forearmPronationSupinationElbowExtendedMtr) +
            parseInt(this.normalReflexActivityMtr)
        );
    },
    wrist(){
        return(
            parseInt(this.wristStabilityElbowAt90Mtr) +
            parseInt(this.wristFlexionExtensionElbowAt90Mtr) +
            parseInt(this.wristStabilityElbowExtendedMtr) +
            parseInt(this.wristFlexionExtensionElbowExtendedMtr) +
            parseInt(this.wristCircumductionMtr)
        );
    },
    hand(){
        return(
            parseInt(this.fingersMassFlexionMtr) +
            parseInt(this.fingersMassExtensionMtr) +
            parseInt(this.distalFingerGraspHookGraspMtr) +
            parseInt(this.thumbAdductionGraspMtr) +
            parseInt(this.thumbToIndexFingerGraspMtr) +
            parseInt(this.cylindricalGraspMtr) +
            parseInt(this.sphericalGraspMtr)
        );
    },
    cs(){
        return(
            parseInt(this.tremorMtr) +
            parseInt(this.dysmetriaMtr) +
            parseInt(this.speedMtr) 
        );
    },
    sensationB() {
        return(
            parseInt(this.lightTouchUpperArmForearmSnt) +
            parseInt(this.lightTouchPalmarSurfaceOfHandSnt) +
            parseInt(this.positionShoulderSnt) +
            parseInt(this.positionElbowSnt) +
            parseInt(this.positionWristSnt) +
            parseInt(this.positionThumbSnt)
        );
    },
    pjtC() {
        return(
            parseInt(this.shoulderFlexion0180Pjt) +
            parseInt(this.shoulderAbduction090Pjt) +
            parseInt(this.externalRotationPjt) +
            parseInt(this.internalRotationPjt) +
            parseInt(this.elbowFlexionPjt) +
            parseInt(this.elbowExtensionPjt) +
            parseInt(this.forearmPronationPjt) +
            parseInt(this.forearmSupinationPjt) +
            parseInt(this.wristFlexionPjt) +
            parseInt(this.wristExtensionPjt) +
            parseInt(this.fingersFlexionPjt) +
            parseInt(this.fingersExtensionPjt)
        );
    },
    jpD() {
      return (
        parseInt(this.shoulderFlexion0180Jp) +
        parseInt(this.shoulderAbduction090Jp) +
        parseInt(this.externalRotationJp) +
        parseInt(this.internalRotationJp) +
        parseInt(this.elbowFlexionJp) +
        parseInt(this.elbowExtensionJp) +
        parseInt(this.forearmPronationJp) +
        parseInt(this.forearmSupinationJp) +
        parseInt(this.wristFlexionJp) +
        parseInt(this.wristExtensionJp) +
        parseInt(this.fingersFlexionJp) +
        parseInt(this.fingersExtensionJp)
      );
    },
    
  },
  methods:{
    increasePage(){
      if(this.part<3){
        this.part += 1;
      }
    },
    decreasePage(){
      if (this.part>1){
        this.part -= 1;
      }
    },
    computeScore(){
      // let formData = [];
      this.formData.push([
        this.elbowFlexionMtr, this.shoulderAdductionInternalRotationMtr, this.fingersMassFlexionMtr,
        this.shoulderElevationMtr, this.fingersMassExtensionMtr, this.cylindricalGraspMtr,
        this.tremorMtr, this.forearmPronationMtr, this.elbowExtensionMtr, this.shoulderAbductionMtr,
        this.handToLumbarSpineMtr, this. shoulderFlexion090ElbowExtendedMtr, this.forearmPronationSupinationElbowAt90Mtr,
        this.shoulderRetractionMtr, this.thumbToIndexFingerGraspMtr, this.wristFlexionExtensionElbowAt90Mtr, this.wristStabilityElbowAt90Mtr,
        this.shoulderExternalRotationMtr, this.dysmetriaMtr, this.shoulderAbduction090ElbowExtendedMtr, this.forearmSupinationMtr,
        this.speedMtr, this.wristStabilityElbowExtendedMtr, this.forearmPronationSupinationElbowExtendedMtr,
        this.wristFlexionExtensionElbowExtendedMtr, this.thumbAdductionGraspMtr, this.sphericalGraspMtr,
        this.shoulderFlexion90180ElbowExtendedMtr, this.distalFingerGraspHookGraspMtr, this.wristCircumductionMtr
      ]);
      let flag = false;
      let startIndex = 0;
      let checkVal = 0;

      if (this.part == 3){
        // console.log("reached: " + this.formData[0].length)
        while (flag === false && startIndex < this.formData[0].length) {
        
        if (this.formData[0][startIndex] === "") {
          console.log(`index ${startIndex} empty`);
          flag = true;
        }
          console.log(` starting turn ${startIndex + 1}`);
        if (this.formData[0][startIndex] < this.formData[0][0]) {
          // reset checkVal variable;
          checkVal = 0;
          // check the any indexes meets requirement
          if (this.formData[0][startIndex + 1] < this.formData[0][0]) {
            checkVal += 1;
          }
          if (this.formData[0][startIndex + 2] < this.formData[0][0]) {
            checkVal += 1;
          }
          if (this.formData[0][startIndex + 3] < this.formData[0][0]) {
            checkVal += 1;
          }
          if (this.formData[0][startIndex + 4] < this.formData[0][0]) {
            checkVal += 1;
          }
          if (checkVal >= 3) {
            console.log(`index ${startIndex} meets requirement`);
            flag = true;
            document.getElementById("alert-banner").innerHTML = `
            <div class="alert alert-success d-flex align-items-center" role="alert">
              <svg class="bi flex-shrink-0 me-2" width="24" height="24" role="img" aria-label="Success:"><use xlink:href="#check-circle-fill"/></svg>
              <div>
                Computation successful.
              </div>
              <button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"></button>
            </div>`
          }
        } else {
          startIndex++;
        }
        console.log(`start index: ${startIndex}, form data length: ${this.formData[0].length}
                      check val: ${checkVal}`)
        if(startIndex == this.formData[0].length && checkVal<3){
          console.log(`index ${startIndex} reached. none meets requirement.`)
          document.getElementById("alert-banner").innerHTML = `
          <div class="alert alert-danger alert-dismissible fade show" role="alert">
            <svg class="bi flex-shrink-0 me-2" width="24" height="24" role="img" aria-label="Danger:"><use xlink:href="#exclamation-triangle-fill"/></svg>
            No index meets requirement.
            <button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"></button>
          </div>`
        }
      }
      }

      return console.log("computation end")
    }
  }
};
</script>
<style>
.custom-radio {
  vertical-align: middle;
  margin: 0;
}
</style>
