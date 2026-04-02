# params 
 {'predict_dates': [{'start': '2026-04-02', 'end': '2026-04-02'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260402_16 224037896967284000 (Recorders: 4/5)

	Recorder: e1b2b89567fb4070a54280001b8a9dfd

		Model: {'id': 'e1b2b89567fb4070a54280001b8a9dfd', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.04, 'Rank IC': 0.033, 'Rank ICIR': 0.159}, 'data_train_vec': ['2021-04-02', '2025-01-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.159', 'weight': '0.040'}

	Recorder: b3e57759c9ef4a53a43ae1df0437a062

		Model: {'id': 'b3e57759c9ef4a53a43ae1df0437a062', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.278, 'Rank IC': 0.053, 'Rank ICIR': 0.327}, 'data_train_vec': ['2023-04-02', '2025-07-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.327', 'weight': '0.083'}

	Recorder: 82d49778c3b84d2ab9f36e94abc08b58

		Model: {'id': '82d49778c3b84d2ab9f36e94abc08b58', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.039, 'Rank IC': 0.04, 'Rank ICIR': 0.317}, 'data_train_vec': ['2024-04-02', '2025-10-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.317', 'weight': '0.080'}

	Recorder: 3bd1fb0612f640929efa2d2765e4aa9a

		Model: {'id': '3bd1fb0612f640929efa2d2765e4aa9a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.104, 'Rank IC': 0.002, 'Rank ICIR': 0.017}, 'data_train_vec': ['2025-04-02', '2026-01-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.017', 'weight': '0.004'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260402_16 688051544509540887 (Recorders: 3/5)

	Recorder: 5f31b5414b6942b09ce7524c491fd7a3

		Model: {'id': '5f31b5414b6942b09ce7524c491fd7a3', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.017, 'Rank IC': 0.024, 'Rank ICIR': 0.155}, 'data_train_vec': ['2021-04-02', '2025-01-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.155', 'weight': '0.039'}

	Recorder: facf6bc261c6434480151b9e0a37352d

		Model: {'id': 'facf6bc261c6434480151b9e0a37352d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.037, 'Rank IC': 0.046, 'Rank ICIR': 0.267}, 'data_train_vec': ['2023-04-02', '2025-07-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.267', 'weight': '0.068'}

	Recorder: 317c2adb3793427c86a412be802f7533

		Model: {'id': '317c2adb3793427c86a412be802f7533', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.246, 'Rank IC': 0.04, 'Rank ICIR': 0.353}, 'data_train_vec': ['2024-04-02', '2025-10-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.353', 'weight': '0.089'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260402_14 791415597451679387 (Recorders: 4/5)

	Recorder: 5f55f143d90f4aa3a23d5b62a9485ee9

		Model: {'id': '5f55f143d90f4aa3a23d5b62a9485ee9', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.119, 'Rank IC': 0.039, 'Rank ICIR': 0.221}, 'data_train_vec': ['2021-04-02', '2025-01-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.221', 'weight': '0.056'}

	Recorder: 9f2dc24c2e714db1812f51e0649b734c

		Model: {'id': '9f2dc24c2e714db1812f51e0649b734c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.02, 'Rank IC': 0.028, 'Rank ICIR': 0.16}, 'data_train_vec': ['2022-04-02', '2025-04-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.160', 'weight': '0.041'}

	Recorder: 392870de8906484192f6af5988beeb47

		Model: {'id': '392870de8906484192f6af5988beeb47', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.106, 'Rank IC': 0.051, 'Rank ICIR': 0.293}, 'data_train_vec': ['2023-04-02', '2025-07-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.293', 'weight': '0.074'}

	Recorder: 939ee96c2b8e450b9416c5ee36839439

		Model: {'id': '939ee96c2b8e450b9416c5ee36839439', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.248, 'Rank IC': 0.039, 'Rank ICIR': 0.373}, 'data_train_vec': ['2024-04-02', '2025-10-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.373', 'weight': '0.095'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260402_13 244830570259083296 (Recorders: 3/5)

	Recorder: e864b1b0a0204ed58369b724c2aeec20

		Model: {'id': 'e864b1b0a0204ed58369b724c2aeec20', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.107, 'Rank IC': 0.024, 'Rank ICIR': 0.193}, 'data_train_vec': ['2021-04-02', '2025-01-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.193', 'weight': '0.049'}

	Recorder: 39f275b964a84835b953153fe55131ae

		Model: {'id': '39f275b964a84835b953153fe55131ae', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.03, 'Rank IC': 0.021, 'Rank ICIR': 0.178}, 'data_train_vec': ['2022-04-02', '2025-04-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.178', 'weight': '0.045'}

	Recorder: 65ef0c975ce14b769398b5a559bba1b0

		Model: {'id': '65ef0c975ce14b769398b5a559bba1b0', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.113, 'Rank IC': 0.039, 'Rank ICIR': 0.327}, 'data_train_vec': ['2023-04-02', '2025-07-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.327', 'weight': '0.083'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260402_13 830619523034236321 (Recorders: 4/5)

	Recorder: cd392d8d073c472180225a146059a2cb

		Model: {'id': 'cd392d8d073c472180225a146059a2cb', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.064, 'Rank IC': 0.03, 'Rank ICIR': 0.16}, 'data_train_vec': ['2021-04-02', '2025-01-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.160', 'weight': '0.041'}

	Recorder: c38e4fadb9c94f2ab165779fc337bc15

		Model: {'id': 'c38e4fadb9c94f2ab165779fc337bc15', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.018, 'Rank IC': 0.026, 'Rank ICIR': 0.15}, 'data_train_vec': ['2022-04-02', '2025-04-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.150', 'weight': '0.038'}

	Recorder: e65386e68aa64ffe8c68137eb06403a3

		Model: {'id': 'e65386e68aa64ffe8c68137eb06403a3', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.043, 'Rank IC': 0.043, 'Rank ICIR': 0.252}, 'data_train_vec': ['2023-04-02', '2025-07-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.252', 'weight': '0.064'}

	Recorder: 515e9e36745d4f43866ea7e8966b0b74

		Model: {'id': '515e9e36745d4f43866ea7e8966b0b74', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.07, 'Rank IC': 0.005, 'Rank ICIR': 0.044}, 'data_train_vec': ['2025-04-02', '2026-01-01'], 'train_time_vec': ['2026-04-02', '2026-04-02'], 'rank_icir': '0.044', 'weight': '0.011'}
