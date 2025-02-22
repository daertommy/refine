---
title: Introduction
slug: /packages/documentation/tanstack-table/introduction
source: /packages/react-table/src/useTable
sidebar_label: Introduction
---

import BaseHeadlessTable from "./examples/headless";
import BaseMantineTable from "./examples/mantine";
import BaseChakraUiTable from "./examples/chakra-ui";

# TanStack Table <GuideBadge id="guides-concepts/tables" /> <RouterBadge id="guides-concepts/routing/#usetable" />

Refine provides an integration package for [TanStack Table][tanstack-table] library. This package enables you to manage your tables in a headless manner. This adapter supports all of the features of both [TanStack Table][tanstack-table] and [Refine's useTable][use-table-core] hook (sorting, filtering pagination etc). Simply, you can use any of the [TanStack Table][tanstack-table] examples as-is by copying and pasting them into your project.

## Installation

Install the [`@refinedev/react-table`][refine-react-table] library.

<Tabs
defaultValue="npm"
values={[
{label: 'npm', value: 'npm'},
{label: 'yarn', value: 'yarn'},
{label: 'pnpm', value: 'pnpm'}
]}>

<TabItem value="npm">

```bash
npm i @refinedev/react-table
```

</TabItem>

<TabItem value="yarn">

```bash
yarn add @refinedev/react-table
```

</TabItem>

<TabItem value="pnpm">

```bash
pnpm add @refinedev/react-table
```

</TabItem>

</Tabs>

## Usage

Let's see how to display a table with [useTable][use-table-tanstack] hook.

We provide implementation examples for the Mantine and Chakra UI. If you using a different ui library, you can use the headless example as a starting point.

<Tabs wrapContent={false}>

<TabItem value="headless" label="Headless">

<BaseHeadlessTable />

</TabItem>

<TabItem value="mantine" label={(<span><span className="block">Mantine</span><small className="block">TanStack Table</small></span>)}>

<BaseMantineTable />

</TabItem>

<TabItem value="chakra-ui" label={(<span><span className="block">Chakra UI</span><small className="block">TanStack Table</small></span>)}>

<BaseChakraUiTable />

</TabItem>

</Tabs>

[tanstack-table]: https://tanstack.com/table/v8
[refine-react-table]: https://github.com/refinedev/refine/tree/master/packages/react-table
[use-table-core]: /docs/api-reference/core/hooks/useTable
[use-table-tanstack]: /docs/packages/documentation/tanstack-table/use-form/
[baserecord]: /api-reference/core/interfaces.md#baserecord
[httperror]: /api-reference/core/interfaces.md#httperror
[syncwithlocationparams]: /api-reference/core/interfaces.md#syncwithlocationparams
[notification-provider]: /api-reference/core/providers/notification-provider.md
[crudsorting]: /api-reference/core/interfaces.md#crudsorting
[crudfilters]: /api-reference/core/interfaces.md#crudfilters
[refine swl]: /api-reference/core/components/refine-config.md#syncwithlocation
