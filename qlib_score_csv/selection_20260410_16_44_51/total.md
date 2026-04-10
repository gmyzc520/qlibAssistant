# params 
 {'predict_dates': [{'start': '2026-04-10', 'end': '2026-04-10'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260410_16 351503731439357325 (Recorders: 3/5)

	Recorder: 8ff3ebb2ebd94e288e0541fecc27f454

		Model: {'id': '8ff3ebb2ebd94e288e0541fecc27f454', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.202, 'Rank IC': 0.036, 'Rank ICIR': 0.222}, 'data_train_vec': ['2023-04-10', '2025-07-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.222', 'weight': '0.080'}

	Recorder: 4455d286ccee4320a2f01fbcacc1fb6b

		Model: {'id': '4455d286ccee4320a2f01fbcacc1fb6b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.085, 'Rank IC': 0.028, 'Rank ICIR': 0.207}, 'data_train_vec': ['2024-04-10', '2025-10-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.207', 'weight': '0.074'}

	Recorder: 8cc2c3439ab64cc5b8ad4d0dc124658c

		Model: {'id': '8cc2c3439ab64cc5b8ad4d0dc124658c', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.097, 'Rank IC': 0.003, 'Rank ICIR': 0.025}, 'data_train_vec': ['2025-04-10', '2026-01-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.025', 'weight': '0.009'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260410_16 451680893609551620 (Recorders: 1/5)

	Recorder: 2b94a046550b4409883a27c639fe5597

		Model: {'id': '2b94a046550b4409883a27c639fe5597', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.326, 'Rank IC': 0.044, 'Rank ICIR': 0.391}, 'data_train_vec': ['2024-04-10', '2025-10-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.391', 'weight': '0.140'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260410_13 117863036524518210 (Recorders: 3/5)

	Recorder: 6369077c7c42484bb6fdbf69384c3ce7

		Model: {'id': '6369077c7c42484bb6fdbf69384c3ce7', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.063, 'Rank IC': 0.028, 'Rank ICIR': 0.163}, 'data_train_vec': ['2021-04-10', '2025-01-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.163', 'weight': '0.058'}

	Recorder: d72df1bb0a3b485ca0daf718f27a65f9

		Model: {'id': 'd72df1bb0a3b485ca0daf718f27a65f9', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.082, 'Rank IC': 0.044, 'Rank ICIR': 0.254}, 'data_train_vec': ['2023-04-10', '2025-07-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.254', 'weight': '0.091'}

	Recorder: 7d2d563d624444a29fce009c126c8e43

		Model: {'id': '7d2d563d624444a29fce009c126c8e43', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.239, 'Rank IC': 0.026, 'Rank ICIR': 0.227}, 'data_train_vec': ['2024-04-10', '2025-10-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.227', 'weight': '0.081'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260410_13 748175747706441933 (Recorders: 5/5)

	Recorder: 975cd9108e414f64835dadd590c49c7c

		Model: {'id': '975cd9108e414f64835dadd590c49c7c', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.088, 'Rank IC': 0.021, 'Rank ICIR': 0.17}, 'data_train_vec': ['2021-04-10', '2025-01-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.170', 'weight': '0.061'}

	Recorder: 65a2e3568a4b44e686b08b171f16f1e5

		Model: {'id': '65a2e3568a4b44e686b08b171f16f1e5', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.017, 'Rank IC': 0.019, 'Rank ICIR': 0.167}, 'data_train_vec': ['2022-04-10', '2025-04-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.167', 'weight': '0.060'}

	Recorder: d33c99ad27564aae81fafcc333b3b31f

		Model: {'id': 'd33c99ad27564aae81fafcc333b3b31f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.12, 'Rank IC': 0.038, 'Rank ICIR': 0.327}, 'data_train_vec': ['2023-04-10', '2025-07-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.327', 'weight': '0.117'}

	Recorder: 4ba4447c599d4725909970dbc3cdecc3

		Model: {'id': '4ba4447c599d4725909970dbc3cdecc3', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.055, 'Rank IC': 0.008, 'Rank ICIR': 0.064}, 'data_train_vec': ['2024-04-10', '2025-10-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.064', 'weight': '0.023'}

	Recorder: 6071274678264fd591639b64eb6701bc

		Model: {'id': '6071274678264fd591639b64eb6701bc', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.081, 'Rank IC': 0.003, 'Rank ICIR': 0.019}, 'data_train_vec': ['2025-04-10', '2026-01-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.019', 'weight': '0.007'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260410_13 920929484397986946 (Recorders: 3/5)

	Recorder: b500eb1880dd4780945bca184642baa6

		Model: {'id': 'b500eb1880dd4780945bca184642baa6', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.035, 'Rank IC': 0.018, 'Rank ICIR': 0.097}, 'data_train_vec': ['2021-04-10', '2025-01-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.097', 'weight': '0.035'}

	Recorder: fb4a416c9c084aa889dc692095d02e95

		Model: {'id': 'fb4a416c9c084aa889dc692095d02e95', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.019, 'Rank IC': 0.031, 'Rank ICIR': 0.173}, 'data_train_vec': ['2023-04-10', '2025-07-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.173', 'weight': '0.062'}

	Recorder: 5f2f27c17ee242189fbdefe50a063b74

		Model: {'id': '5f2f27c17ee242189fbdefe50a063b74', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.07, 'Rank IC': 0.034, 'Rank ICIR': 0.284}, 'data_train_vec': ['2024-04-10', '2025-10-09'], 'train_time_vec': ['2026-04-10', '2026-04-10'], 'rank_icir': '0.284', 'weight': '0.102'}
