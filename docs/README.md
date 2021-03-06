# Csound Plugins

## else

Miscellaneous plugins

  * [accum](opcodes/accum.md): Simple accumulator of scalar values
  * [atstop](opcodes/atstop.md): Schedule an instrument at the end of the current instrument
  * [crackle](opcodes/crackle.md): generates noise based on a chaotic equation
  * [defer](opcodes/defer.md): Run an opcode at the end of an event
  * [deref](opcodes/deref.md): Dereference a previously created reference to a variable
  * [diode_ringmod](opcodes/diode_ringmod.md): A ring modulator with optional non-linearities
  * [file_exists](opcodes/file_exists.md): Returns 1 if a file exists and can be read
  * [frac2int](opcodes/frac2int.md): Convert the fractional part of a number into an integer
  * [lfnoise](opcodes/lfnoise.md): low frequency, band-limited noise
  * [linenv](opcodes/linenv.md): A triggerable linear envelope with sustain segment
  * [memview](opcodes/memview.md): Create a view into a table or another array
  * [pread](opcodes/pread.md): Read pfield values from any active instrument instance
  * [pwrite](opcodes/pwrite.md): Modify pfield values of an active instrument instance
  * [ramptrig](opcodes/ramptrig.md): A triggerable ramp between 0 and 1
  * [ref](opcodes/ref.md): Get a reference to a variable
  * [refvalid](opcodes/refvalid.md): Queries if a reference is valid
  * [schmitt](opcodes/schmitt.md): A schmitt trigger (a comparator with hysteresis).
  * [sigmdrive](opcodes/sigmdrive.md): Analog "soft clipping" distortion by applying non-linear transfer functions.
  * [standardchaos](opcodes/standardchaos.md): Standard map chaotic generator
  * [uniqinstance](opcodes/uniqinstance.md): Return an fractional instrument number which is not in use
  * [xtracycles](opcodes/xtracycles.md): Returns the number of extra performance cycles for an event

## jsfx

Jesusonics effects in csound

  * [jsfx](opcodes/jsfx.md): Instantiates and runs a jsfx script
  * [jsfx_getslider](opcodes/jsfx_getslider.md): Gets a slider value of a jsfx instance
  * [jsfx_new](opcodes/jsfx_new.md): Instantiates a jsfx script
  * [jsfx_play](opcodes/jsfx_play.md): Processes audio through a jsfx script
  * [jsfx_setslider](opcodes/jsfx_setslider.md): Sets the slider values of a jsfx script
  * [tubeharmonics](opcodes/tubeharmonics.md): A distortion with control for odd/even harmonics

## klib

hashtable / pool / string cache plugins

  * [dict_exists](opcodes/dict_exists.md): Returns 1 if the dict exists, 0 otherwise
  * [dict_free](opcodes/dict_free.md): Free a hashtable
  * [dict_get](opcodes/dict_get.md): Get a value from a hashtable
  * [dict_iter](opcodes/dict_iter.md): Iterate over the key-value pairs of a dict
  * [dict_new](opcodes/dict_new.md): Create a hashtable
  * [dict_print](opcodes/dict_print.md): Prints the contents of a dict
  * [dict_query](opcodes/dict_query.md): Query different properties of a dict
  * [dict_set](opcodes/dict_set.md): Set (or remove) a value from a hashtable
  * [dict_size](opcodes/dict_size.md): Returns the number of key:value pairs in a dict
  * [pool_at](opcodes/pool_at.md): Returns the item of a pool at a given index
  * [pool_capacity](opcodes/pool_capacity.md): Returns the capacity of a pool
  * [pool_gen](opcodes/pool_gen.md): Create a pool and fill it with values
  * [pool_new](opcodes/pool_new.md): Create an empty  pool
  * [pool_pop](opcodes/pool_pop.md): Pop (get) an item from a pool
  * [pool_push](opcodes/pool_push.md): Push an item into a pool
  * [pool_size](opcodes/pool_size.md): Returns the size of a pool
  * [strcache](opcodes/strcache.md): Put a string into the global cache or retrieve a string from the cache
  * [strview](opcodes/strview.md): Retrieves a read-only string from the cache

## mverb

Artificial reverb based on a 2D waveguide mesh

  * [MVerb](opcodes/MVerb.md): MVerb - Implements Jon Christopher Nelson's waveguide mesh reverb.

## poly

Run multiple copies of an opcode in parallel/series

  * [poly](opcodes/poly.md): `poly` creates and controls multiple parallel version of an opcode
  * [poly0](opcodes/poly0.md): `poly0` creates and controls multiple parallel version of an opcode with no outputs
  * [polyseq](opcodes/polyseq.md): `polyseq` creates and controls multiple **sequential** version of an opcode

## rory

Opcodes to save/recall channels, triggers, etc

  * [channelStateRecall](opcodes/channelStateRecall.md): Recalls channel data saved to a file via `channelStateSave`
  * [channelStateSave](opcodes/channelStateSave.md): Saves all channel data to file
  * [trigExpseg](opcodes/trigExpseg.md): Trace a series of exponential segments between specified points.
  * [trigLinseg](opcodes/trigLinseg.md): Trace a series of line segments between specified points.
