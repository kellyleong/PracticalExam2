SEEM3650 Practical Exam 2 Report
Name: Leong Chi Kei
Student ID: 1155211292


Train the Shakespeare Character-level Model:
First 5 lines of generated shakespeare_char samples:
KING RICHARD II:
Shall I be that set up your hands to my comfort?
DUKE OF YORK:
Then be petition enjoy'd my tents,
And I must be so too with me:


Model Architecture Exploration:
Validation Loss at Iteration 5000 (Layers = 5):
- Heads = 2: 1.5143
- Heads = 3: 1.5447
- Heads = 5: 1.5875
- Heads = 7: 1.5909

The lowest validation loss achieved: 1.5143, with setting using layers = 5 and heads = 2


Training BabyGPT for Code Generation:
- C code from the Redis open-source GitHub repository
- Total Tokens:
train has 593,316 tokens
val has 65,924 tokens
593,316 + 65,924 = 659,240 tokens
so Total Tokens: 659,240


First 20 lines of generated code samples:

               * processed so we are no context it, we'll see this don't reset to because the client as
            * info formattion, should name. */
                 server.master_last_count = 0;

               if (!c->io_flags & CLIENT_MASTER) {
                           rejectCommand(c, shared.commandslaveerr);
                     }
                   return C_OK;
                     }

             /* Assume */
            c->io_curr_repl_off = current_cron += current_pending;
         
---------------

                      return 0;
               }
           }
          /* Note that appleacy examples and applied and API to different
            * was return the same allocative is only performination. */


Favorite snippet:

c->slowlog_time_us_max = new_as_sum;
           c->slowlog_time_us_max = 0;
           c->slowlog_count = 0;

       /* Create that reply incrementally was a reply only write to slaves
        * it is a low to used from lation, a trim the will because the slowlog log. */
        if (!server.unixtime-slowlog_time_ustime && is_slowlog_recla_cmd_time) {
              luaEndOuble(pending_reply, slave->slot);
                lookupCommand();

