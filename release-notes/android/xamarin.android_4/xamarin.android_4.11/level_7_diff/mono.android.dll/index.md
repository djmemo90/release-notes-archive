---
id: 63FA0D25-D895-4C8A-98FA-23114E5FE455
title: "Mono.Android.dll"
---

# Mono.Android.dll

## Namespace Android.AccessibilityServices

### Type Changed: Android.AccessibilityServices.FeedbackFlags

Removed values:

```
AllMask = -1,
	Braille = 32,
```

## Namespace Android.Accounts

### Type Changed: Android.Accounts.AccountManager

Added fields:

```
[Obsolete ("This constant will be removed in the future version. Use Android.Accounts.ErrorCode enum directly instead of this field.")]
	public static const ErrorCode ErrorCodeBadArguments;

	[Obsolete ("This constant will be removed in the future version. Use Android.Accounts.ErrorCode enum directly instead of this field.")]
	public static const ErrorCode ErrorCodeBadRequest;

	[Obsolete ("This constant will be removed in the future version. Use Android.Accounts.ErrorCode enum directly instead of this field.")]
	public static const ErrorCode ErrorCodeCanceled;

	[Obsolete ("This constant will be removed in the future version. Use Android.Accounts.ErrorCode enum directly instead of this field.")]
	public static const ErrorCode ErrorCodeInvalidResponse;

	[Obsolete ("This constant will be removed in the future version. Use Android.Accounts.ErrorCode enum directly instead of this field.")]
	public static const ErrorCode ErrorCodeNetworkError;

	[Obsolete ("This constant will be removed in the future version. Use Android.Accounts.ErrorCode enum directly instead of this field.")]
	public static const ErrorCode ErrorCodeRemoteException;

	[Obsolete ("This constant will be removed in the future version. Use Android.Accounts.ErrorCode enum directly instead of this field.")]
	public static const ErrorCode ErrorCodeUnsupportedOperation;
```

## Namespace Android.Bluetooth

### Type Changed: Android.Bluetooth.BluetoothClass

### Type Changed: Android.Bluetooth.BluetoothClass.Device

Added fields:

```
[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass AudioVideoCamcorder;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass AudioVideoCarAudio;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass AudioVideoHandsfree;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass AudioVideoHeadphones;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass AudioVideoHifiAudio;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass AudioVideoLoudspeaker;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass AudioVideoMicrophone;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass AudioVideoPortableAudio;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass AudioVideoSetTopBox;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass AudioVideoUncategorized;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass AudioVideoVcr;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass AudioVideoVideoCamera;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass AudioVideoVideoConferencing;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass AudioVideoVideoDisplayAndLoudspeaker;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass AudioVideoVideoGamingToy;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass AudioVideoVideoMonitor;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass AudioVideoWearableHeadset;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass ComputerDesktop;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass ComputerHandheldPcPda;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass ComputerLaptop;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass ComputerPalmSizePcPda;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass ComputerServer;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass ComputerUncategorized;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass ComputerWearable;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass HealthBloodPressure;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass HealthDataDisplay;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass HealthGlucose;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass HealthPulseOximeter;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass HealthPulseRate;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass HealthThermometer;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass HealthUncategorized;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass HealthWeighing;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass PhoneCellular;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass PhoneCordless;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass PhoneIsdn;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass PhoneModemOrGateway;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass PhoneSmart;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass PhoneUncategorized;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass ToyController;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass ToyDollActionFigure;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass ToyGame;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass ToyRobot;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass ToyUncategorized;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass ToyVehicle;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass WearableGlasses;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass WearableHelmet;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass WearableJacket;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass WearablePager;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass WearableUncategorized;

	[Obsolete ("This constant will be removed in the future version. Use Android.Bluetooth.DeviceClass enum directly instead of this field.")]
	public static const DeviceClass WearableWristWatch;
```

## Namespace Android.Content.PM

### Type Changed: Android.Content.PM.ApplicationInfoFlags

Added values:

```
None = 0,
```

### Type Changed: Android.Content.PM.PackageManager

Removed methods:

```
public virtual void SetApplicationEnabledSetting (string packageName, ComponentEnabledState newState, PackageInfoFlags flags);
	public virtual void SetComponentEnabledSetting (Android.Content.ComponentName componentName, ComponentEnabledState newState, PackageInfoFlags flags);
```

Added methods:

```
public virtual void SetApplicationEnabledSetting (string packageName, ComponentEnabledState newState, ComponentEnableOption flags);
	public virtual void SetComponentEnabledSetting (Android.Content.ComponentName componentName, ComponentEnabledState newState, ComponentEnableOption flags);
```

### New Type Android.Content.PM.UiOptions

```
[Serializable]
public enum UiOptions {
	None = 0,
}
```

## Namespace Android.Locations

### Type Changed: Android.Locations.Criteria

Added fields:

```
public static const int NoRequirement;
```

## Namespace Android.Net

### Type Changed: Android.Net.WifiMode

Removed values:

```
FullHighPerf = 3,
```

## Namespace Android.OS

### Type Changed: Android.OS.AsyncTask

Added methods:

```
public System.Threading.Tasks.Task<Java.Lang.Object> GetAsync (long timeout, Java.Util.Concurrent.TimeUnit unit);
	public System.Threading.Tasks.Task<Java.Lang.Object> GetAsync ();
```

## Namespace Android.Test.Mock

### Type Changed: Android.Test.Mock.MockPackageManager

Removed methods:

```
public override void SetApplicationEnabledSetting (string packageName, Android.Content.PM.ComponentEnabledState newState, Android.Content.PM.PackageInfoFlags flags);
	public override void SetComponentEnabledSetting (Android.Content.ComponentName componentName, Android.Content.PM.ComponentEnabledState newState, Android.Content.PM.PackageInfoFlags flags);
```

Added methods:

```
public override void SetApplicationEnabledSetting (string packageName, Android.Content.PM.ComponentEnabledState newState, Android.Content.PM.ComponentEnableOption flags);
	public override void SetComponentEnabledSetting (Android.Content.ComponentName componentName, Android.Content.PM.ComponentEnabledState newState, Android.Content.PM.ComponentEnableOption flags);
```

## Namespace Android.Text.Format

### Type Changed: Android.Text.Format.DayOfWeek

Removed values:

```
MondayBeforeJulianEpoch = 2440585,
```

## Namespace Android.Views

### Type Changed: Android.Views.Keycode

Removed values:

```
ThreeDMode = 206,
```

### Type Changed: Android.Views.MenuPerformFlags

Added values:

```
AppendToGroup = 1,
```

### Type Changed: Android.Views.WindowFeatures

Removed values:

```
ActionBar = 8,
	ActionBarOverlay = 9,
	ActionModeOverlay = 10,
```

### Type Changed: Android.Views.WindowManagerLayoutParams

Removed fields:

```
[Obsolete ("This constant will be removed in the future version. Use Android.Views.WindowManagerEventType enum directly instead of this field.")]
	public static const WindowManagerEventType TypeChanged;
```

### Type Changed: Android.Views.WindowManagerTypes

Added values:

```
Changed = 2,
```

### Removed Type Android.Views.EffectsSurface ### Removed Type Android.Views.KeyModifierBehavior ### Removed Type Android.Views.LayerType ### Removed Type Android.Views.ScrollbarPosition ### Removed Type Android.Views.StatusBarVisibility 



## Namespace Android.Views.InputMethods



### Type Changed: Android.Views.InputMethods.EditorInfo

Added fields:

```
public static const int ImeMaskAction;
	public static const int ImeNull;
```

### Type Changed: Android.Views.InputMethods.ImeAction

Removed values:

```
ImeMaskAction = 255,
	Previous = 7,
```

## Namespace Android.Widget



### Type Changed: Android.Widget.AbsListViewChoiceMode

Removed values:

```
MultipleModal = 3,
```

### Type Changed: Android.Widget.AdapterView

Added fields:

```
public static const int ItemViewTypeHeaderOrFooter;
	public static const int ItemViewTypeIgnore;
```

### Type Changed: Android.Widget.CursorAdapterFlags

Removed values:

```
AutoRequery = 1,
	RegisterContentObserver = 2,
```

### Type Changed: Android.Widget.ListView

Added fields:

```
public static const int ChoiceModeMultiple;
	public static const int ChoiceModeNone;
	public static const int ChoiceModeSingle;
```

### Removed Type Android.Widget.ListPopupWindowInputMethodMode ### Removed Type Android.Widget.NumberPickerScrollState ### Removed Type Android.Widget.ShowDividers ### Removed Type Android.Widget.SpinnerMode 



## Namespace Java.Interop



### Type Changed: Java.Interop.JavaObjectExtensions

Removed methods:

```
public static Android.Runtime.JavaCollection ToInteroperableCollection (System.Collections.ICollection instance);
	public static Android.Runtime.JavaCollection<T> ToInteroperableCollection<T> (System.Collections.Generic.ICollection<T> instance);
	public static Android.Runtime.JavaList ToInteroperableCollection (System.Collections.IList instance);
	public static Android.Runtime.JavaList<T> ToInteroperableCollection<T> (System.Collections.Generic.IList<T> instance);
	public static Android.Runtime.JavaDictionary ToInteroperableCollection (System.Collections.IDictionary instance);
	public static Android.Runtime.JavaDictionary<K,V> ToInteroperableCollection<K, V> (System.Collections.Generic.IDictionary<K,V> instance);
```

Added methods:

```
[Obsolete ("Use Android.Runtime.JavaCollection.ToLocalJniHandle()")]
	public static Android.Runtime.JavaCollection ToInteroperableCollection (System.Collections.ICollection instance);

	[Obsolete ("Use Android.Runtime.JavaCollection.ToLocalJniHandle()")]
	public static Android.Runtime.JavaCollection<T> ToInteroperableCollection<T> (System.Collections.Generic.ICollection<T> instance);

	[Obsolete ("Use Android.Runtime.JavaList.ToLocalJniHandle()")]
	public static Android.Runtime.JavaList ToInteroperableCollection (System.Collections.IList instance);

	[Obsolete ("Use Android.Runtime.JavaList.ToLocalJniHandle()")]
	public static Android.Runtime.JavaList<T> ToInteroperableCollection<T> (System.Collections.Generic.IList<T> instance);

	[Obsolete ("Use Android.Runtime.JavaDictionary.ToLocalJniHandle()")]
	public static Android.Runtime.JavaDictionary ToInteroperableCollection (System.Collections.IDictionary instance);

	[Obsolete ("Use Android.Runtime.JavaDictionary.ToLocalJniHandle()")]
	public static Android.Runtime.JavaDictionary<K,V> ToInteroperableCollection<K, V> (System.Collections.Generic.IDictionary<K,V> instance);
```

## Namespace Java.Util.Prefs



### Type Changed: Java.Util.Prefs.Preferences

Added methods:

```
public System.Threading.Tasks.Task ExportNodeAsync (System.IO.Stream ostream);
	public System.Threading.Tasks.Task ExportSubtreeAsync (System.IO.Stream ostream);
	public System.Threading.Tasks.Task FlushAsync ();
	public static System.Threading.Tasks.Task ImportPreferencesAsync (System.IO.Stream istream);
	public System.Threading.Tasks.Task SyncAsync ();
```

## Namespace Org.Apache.Http.Conn.Ssl



### Type Changed: Org.Apache.Http.Conn.Ssl.SSLSocketFactory

Added methods:

```
public System.Threading.Tasks.Task<Java.Net.Socket> ConnectSocketAsync (Java.Net.Socket sock, string host, int port, Java.Net.InetAddress localAddress, int localPort, Org.Apache.Http.Params.IHttpParams params);
	public System.Threading.Tasks.Task<Java.Net.Socket> CreateSocketAsync ();
	public System.Threading.Tasks.Task<Java.Net.Socket> CreateSocketAsync (Java.Net.Socket socket, string host, int port, bool autoClose);
```
