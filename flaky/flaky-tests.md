# Flaky Test Report - 2026-08-23

## Summary

- **Flaky tests**: 10
- **Newly flaky** (last 7 days): 10
- **Resolved**: 0
- **Total tests analyzed**: 31570
- **CI runs analyzed**: 45

---

## Flaky Tests

| Test | Failure Rate | Failures | Flaky Score | Last Failed |
|------|--------------|----------|-------------|-------------|
| `..._rsample_and_log_prob[device0-True-False--1.0-1.0-dtype1]` 🆕 | 8.7% (12/138) | 12 | 0.17 | 2026-08-21 |
| `..._rsample_and_log_prob[device0-True-False--2.0-3.0-dtype0]` 🆕 | 8.7% (12/138) | 12 | 0.17 | 2026-08-21 |
| `..._rsample_and_log_prob[device0-True-False--2.0-3.0-dtype1]` 🆕 | 8.7% (12/138) | 12 | 0.17 | 2026-08-21 |
| `...s_kwargs_have_config_fields[TensorDictReplayBufferConfig]` 🆕 | 8.7% (12/138) | 12 | 0.17 | 2026-08-21 |
| `..._rsample_and_log_prob[device0-True-False--1.0-1.0-dtype0]` 🆕 | 8.7% (12/138) | 12 | 0.17 | 2026-08-21 |
| `...s/test_tqc.py::TestTQC::test_tqc_numerical_contract[True]` 🆕 | 8.7% (12/138) | 12 | 0.17 | 2026-08-21 |
| `...stDiffusionActor::test_reduced_precision_schedule[dtype0]` 🆕 | 8.6% (10/116) | 10 | 0.17 | 2026-08-21 |
| `...t_rb_core.py::test_replay_buffer_prefetch_dumps_roundtrip` 🆕 | 7.2% (10/138) | 10 | 0.14 | 2026-08-21 |
| `...py::TestDreamerV3Components::test_block_gru_torch_compile` 🆕 | 7.2% (10/138) | 10 | 0.14 | 2026-08-20 |
| `...core.py::test_replay_buffer_prefetch_state_dict_roundtrip` 🆕 | 5.8% (8/138) | 8 | 0.12 | 2026-08-21 |


### Newly Flaky Tests

- `test/test_distributions.py::TestTanhNormal::test_tanhnormal_rsample_and_log_prob[device0-True-False--1.0-1.0-dtype1]`
- `test/test_distributions.py::TestTanhNormal::test_tanhnormal_rsample_and_log_prob[device0-True-False--2.0-3.0-dtype0]`
- `test/test_distributions.py::TestTanhNormal::test_tanhnormal_rsample_and_log_prob[device0-True-False--2.0-3.0-dtype1]`
- `test/test_configs.py::TestConfigClassParity::test_wrapped_class_kwargs_have_config_fields[TensorDictReplayBufferConfig]`
- `test/test_distributions.py::TestTanhNormal::test_tanhnormal_rsample_and_log_prob[device0-True-False--1.0-1.0-dtype0]`
- `test/objectives/test_tqc.py::TestTQC::test_tqc_numerical_contract[True]`
- `test/modules/test_actor.py::TestDiffusionActor::test_reduced_precision_schedule[dtype0]`
- `test/rb/test_rb_core.py::test_replay_buffer_prefetch_dumps_roundtrip`
- `test/modules/test_dreamer_components.py::TestDreamerV3Components::test_block_gru_torch_compile`
- `test/rb/test_rb_core.py::test_replay_buffer_prefetch_state_dict_roundtrip`

---

## Configuration

- Minimum failure rate: 5%
- Maximum failure rate: 95%
- Minimum failures required: 2
- Minimum executions required: 3

---

*Generated at 2026-08-23T06:14:01.219267+00:00*