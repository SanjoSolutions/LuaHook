# Hook

A library for providing hooks into functionality. This can help other add-on creators to save some work.

**Functions included:**

* **Hook.Hook**: a class for a hook.
  * **Hook.Hook.new**: the constructor for the hook class.
  * **Hook.Hook:registerCallback**: a method for registering a callback.
  * **Hook.Hook:registerCallbackForRunningOnce**: a method for registering a callback that is only run once.
  * **Hook.Hook:runCallbacks**: a method for running all registered callbacks.
